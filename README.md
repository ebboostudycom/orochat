# OroChat

OroChat is a browser-based, mobile-friendly chat application built by Ebisa Jemal Yuya. It uses Firebase Authentication for account access and Cloud Firestore for user profiles, conversations, and messages.

## Current features

- Email and password registration and sign-in
- Google sign-in (when enabled in Firebase)
- Password reset
- User profile display
- One-to-one text conversations
- Live message updates through Firestore listeners
- Contact discovery
- Light and dark appearance

Some interface controls are placeholders for future work. Voice calls, video calls, notifications, premium subscriptions, and some profile or privacy controls should not be considered implemented unless separately completed and tested.

## Run the app

1. Create or select a Firebase project.
2. Enable **Email/Password** in Firebase Authentication. Enable Google sign-in if you want that option.
3. Create a Cloud Firestore database.
4. Review and configure Firestore Security Rules before allowing real users to use the app. See [FIRESTORE_SECURITY.md](FIRESTORE_SECURITY.md).
5. Check the Firebase configuration in the JavaScript module in `Index.html`. Replace it with the web-app configuration for your own Firebase project if necessary.
6. Serve the repository using a local web server or static hosting. Because the app uses JavaScript modules, opening the HTML file directly with a `file://` URL may not work reliably.
7. Open `Index.html` in a modern browser.

## Data model currently used by the client

The current client expects these Firestore paths and fields:

- `users/{uid}`: `uid`, `name`, `username`, and `email` are read by the interface.
- `chats/{chatId}`: `participants` (an array of two user IDs), `lastMessage`, `lastSenderId`, and `updatedAt`.
- `chats/{chatId}/messages/{messageId}`: `text`, `senderId`, `receiverId`, and `createdAt`.

The client derives a one-to-one chat ID by sorting the two user IDs and joining them with an underscore. Any security rules must validate the authenticated user and both participants; do not rely on the client alone.

## Important security notes

- Never deploy permissive Firestore rules such as `allow read, write: if true`.
- The current client loads user and chat collections and filters them in the browser. This is not a privacy boundary. Review the rules and refactor these queries before using real personal data.
- Avoid exposing email addresses in public contact search. Prefer a minimal public profile document and keep private account information separate.
- Validate message size and all message fields in Firestore rules or trusted server code as well as in the browser.
- Use Firebase App Check and appropriate authentication/provider settings as additional safeguards.
- A Firebase web API key identifies the project; it is not a substitute for Firestore Security Rules.

## Verification status

This repository has not been runtime-tested against your Firebase project as part of this change. The actual deployed Firestore rules, enabled authentication providers, indexes, and hosting configuration must be checked in the Firebase console before production use.

## Project structure

```
.
├── Index.html
├── README.md
└── FIRESTORE_SECURITY.md
```

## License

No license is currently declared in this repository. Add a license file if you want to specify how others may use, modify, and distribute the project.
