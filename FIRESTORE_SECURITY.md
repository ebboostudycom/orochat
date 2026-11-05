# Firestore security review checklist

> This document is guidance, not a deployed Firebase ruleset. The repository does not contain the rules currently deployed in the Firebase project, so no rules are proposed as safe to publish without checking the live data model and testing the app.

## Before launch

- [ ] Open Firebase Console → Firestore Database → Rules and review the rules currently deployed.
- [ ] Confirm that every read and write requires an authenticated user.
- [ ] A user can read or update only their own private profile data.
- [ ] Public contact discovery exposes only fields intended to be public (for example, display name and username), never email addresses or private account metadata.
- [ ] A chat can be read only by a user whose authenticated UID is in that chat's `participants` array.
- [ ] A chat must have exactly the intended two participants for a one-to-one conversation; clients must not be allowed to add arbitrary participants.
- [ ] A message can be created only by a participant in the parent chat.
- [ ] The message `senderId` must equal the authenticated UID.
- [ ] The message `receiverId` must be the other participant.
- [ ] Message text must be a non-empty string with a server-enforced maximum length (the client now limits it to 4,000 characters).
- [ ] Clients cannot rewrite another user's messages or alter immutable sender/creation fields.
- [ ] Chat summary fields such as `lastMessage`, `lastSenderId`, and `updatedAt` are validated and cannot be used to bypass message authorization.
- [ ] Test allowed and denied cases with the Firebase Emulator Suite before deployment.

## Important current-client limitation

The current `Index.html` requests the full `users` collection and the full `chats` collection, then filters the results in the browser. Client-side filtering does not protect data. If rules allow these collection reads, users may receive records they should not see; if rules deny them, those screens may fail.

Before enabling strict rules, refactor the app to query only data the signed-in user is permitted to read. For user discovery, use a deliberately public profile collection with minimal fields (for example, `publicProfiles/{uid}`) and keep email/private fields in `users/{uid}`. For chat lists, query only documents where `participants` contains the current UID, and verify the query is compatible with the deployed rules.

## Do not copy permissive examples

Never use `allow read, write: if true;` or rules that authorize access based only on a client-supplied UID. Firebase Security Rules must use `request.auth.uid` and validate the document relationship. Rules should be tested in the emulator and reviewed against the actual registration, profile, chat, and message writes before publishing.
