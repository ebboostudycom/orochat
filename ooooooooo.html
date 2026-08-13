<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">

<meta name="viewport"
      content="width=device-width,
               initial-scale=1.0,
               maximum-scale=1.0,
               user-scalable=no">

<meta name="theme-color" content="#2563eb">

<title>OroChat</title>

<style>

/* =========================================================
   RESET
========================================================= */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    -webkit-tap-highlight-color:transparent;
}

:root{
    --primary:#2563eb;
    --primary-dark:#1d4ed8;
    --secondary:#0ea5e9;

    --bg:#f4f7fb;
    --card:#ffffff;

    --text:#0f172a;
    --muted:#64748b;

    --border:#e2e8f0;

    --incoming:#ffffff;
    --outgoing:#2563eb;
    --outgoing-text:#ffffff;

    --danger:#dc2626;
    --success:#16a34a;
}

body.dark{
    --bg:#0f172a;
    --card:#1e293b;
    --text:#f8fafc;
    --muted:#94a3b8;
    --border:#334155;

    --incoming:#1e293b;
    --outgoing:#2563eb;
}

html,
body{
    width:100%;
    height:100%;
    overflow:hidden;
}

body{
    font-family:
        Inter,
        system-ui,
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        sans-serif;

    background:var(--bg);
    color:var(--text);
}

button,
input{
    font-family:inherit;
}

button{
    cursor:pointer;
}

button:disabled{
    opacity:.6;
    cursor:not-allowed;
}

#app{
    width:100%;
    height:100%;
    max-width:650px;
    margin:auto;

    background:var(--bg);

    position:relative;
    overflow:hidden;
}

.screen{
    width:100%;
    height:100%;

    display:none;
    flex-direction:column;
}

.screen.active{
    display:flex;
}

/* =========================================================
   ANIMATIONS
========================================================= */

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(5px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}

@keyframes slideUp{
    from{
        transform:translateY(100%);
    }

    to{
        transform:translateY(0);
    }
}

/* =========================================================
   SPLASH
========================================================= */

#splashScreen{
    background:
        linear-gradient(
            145deg,
            var(--primary),
            var(--secondary)
        );

    color:white;

    justify-content:center;
    align-items:center;

    text-align:center;
}

.logo{
    width:105px;
    height:105px;

    background:white;
    color:var(--primary);

    border-radius:32px;

    display:flex;
    align-items:center;
    justify-content:center;

    font-size:55px;

    box-shadow:
        0 20px 50px rgba(0,0,0,.2);

    margin-bottom:25px;
}

.logoText{
    font-size:40px;
    font-weight:800;
}

.tagline{
    margin-top:8px;
    opacity:.85;
}

/* =========================================================
   AUTH
========================================================= */

.auth{
    padding:25px;
    overflow-y:auto;
}

.authLogo{
    text-align:center;
    margin-top:20px;
    margin-bottom:25px;
}

.smallLogo{
    width:75px;
    height:75px;

    border-radius:24px;

    background:var(--primary);
    color:white;

    display:inline-flex;
    align-items:center;
    justify-content:center;

    font-size:38px;
}

.auth h1{
    font-size:30px;
    margin-bottom:8px;
}

.authSubtitle{
    color:var(--muted);
    margin-bottom:25px;
}

.field{
    margin-bottom:16px;
}

.field label{
    display:block;

    font-size:14px;
    font-weight:600;

    margin-bottom:7px;
}

.inputWrap{
    position:relative;
}

.inputBox{
    width:100%;

    border:1px solid var(--border);

    background:var(--card);
    color:var(--text);

    padding:15px 16px;

    border-radius:14px;

    outline:none;

    font-size:16px;
}

.passwordInput{
    padding-right:52px;
}

.inputBox:focus{
    border-color:var(--primary);

    box-shadow:
        0 0 0 3px rgba(37,99,235,.1);
}

.passwordToggle{
    position:absolute;

    right:8px;
    top:50%;

    transform:translateY(-50%);

    border:none;

    background:transparent;

    width:40px;
    height:40px;

    border-radius:50%;

    color:var(--muted);

    font-size:19px;
}

.primaryBtn{
    width:100%;

    border:none;

    background:var(--primary);
    color:white;

    padding:16px;

    border-radius:14px;

    font-size:16px;
    font-weight:700;
}

.primaryBtn:active{
    transform:scale(.98);
}

.googleBtn{
    width:100%;

    padding:14px;

    margin-top:12px;

    background:var(--card);
    color:var(--text);

    border:1px solid var(--border);

    border-radius:14px;

    font-size:15px;
    font-weight:700;

    display:flex;
    align-items:center;
    justify-content:center;

    gap:10px;
}

.googleIcon{
    font-size:20px;
    font-weight:900;
}

.authSwitch{
    text-align:center;

    margin-top:20px;

    color:var(--muted);
}

.link{
    color:var(--primary);

    font-weight:700;

    cursor:pointer;
}

.forgot{
    text-align:right;

    margin:-4px 0 18px;

    color:var(--primary);

    font-size:13px;
    font-weight:700;

    cursor:pointer;
}

.divider{
    display:flex;
    align-items:center;

    gap:12px;

    margin:18px 0;

    color:var(--muted);

    font-size:13px;
}

.divider::before,
.divider::after{
    content:"";

    height:1px;

    flex:1;

    background:var(--border);
}

/* =========================================================
   TOP BAR
========================================================= */

.topBar{
    height:65px;
    min-height:65px;

    display:flex;
    align-items:center;
    justify-content:space-between;

    padding:0 18px;

    background:var(--card);

    border-bottom:1px solid var(--border);
}

.topTitle{
    font-size:23px;
    font-weight:800;
}

.topActions{
    display:flex;
    gap:4px;
}

.iconBtn{
    width:42px;
    height:42px;

    border:none;

    border-radius:50%;

    background:transparent;

    color:var(--text);

    font-size:21px;

    display:flex;
    align-items:center;
    justify-content:center;
}

.iconBtn:active{
    background:var(--bg);
}

/* =========================================================
   SEARCH
========================================================= */

.searchArea{
    padding:12px 16px;

    background:var(--card);
}

.search{
    width:100%;

    padding:13px 16px;

    border:none;

    outline:none;

    border-radius:14px;

    background:var(--bg);

    color:var(--text);

    font-size:15px;
}

/* =========================================================
   CONTENT
========================================================= */

.content{
    flex:1;
    overflow-y:auto;
}

/* =========================================================
   CHAT LIST
========================================================= */

.chatItem{
    display:flex;
    align-items:center;

    padding:14px 17px;

    cursor:pointer;

    border-bottom:1px solid var(--border);

    animation:fadeIn .2s ease;
}

.chatItem:active{
    background:var(--bg);
}

.avatar{
    width:54px;
    height:54px;

    border-radius:50%;

    display:flex;
    align-items:center;
    justify-content:center;

    color:white;

    font-size:21px;
    font-weight:700;

    flex-shrink:0;

    background:
        linear-gradient(
            135deg,
            var(--primary),
            var(--secondary)
        );
}

.chatInfo{
    flex:1;

    min-width:0;

    margin-left:13px;
}

.chatTop{
    display:flex;

    justify-content:space-between;

    gap:10px;
}

.chatName{
    font-weight:700;
}

.chatTime{
    font-size:12px;
    color:var(--muted);
}

.lastMessage{
    margin-top:5px;

    color:var(--muted);

    white-space:nowrap;

    overflow:hidden;

    text-overflow:ellipsis;
}

/* =========================================================
   BOTTOM NAV
========================================================= */

.bottomNav{
    height:70px;
    min-height:70px;

    background:var(--card);

    border-top:1px solid var(--border);

    display:flex;

    justify-content:space-around;
    align-items:center;
}

.navItem{
    flex:1;

    height:100%;

    border:none;

    background:transparent;

    color:var(--muted);

    display:flex;

    flex-direction:column;

    align-items:center;

    justify-content:center;

    gap:4px;

    font-size:12px;
}

.navItem.active{
    color:var(--primary);
    font-weight:700;
}

.navIcon{
    font-size:22px;
}

/* =========================================================
   FAB
========================================================= */

.fab{
    position:absolute;

    right:20px;
    bottom:88px;

    width:58px;
    height:58px;

    border:none;

    border-radius:50%;

    background:var(--primary);

    color:white;

    font-size:25px;

    box-shadow:
        0 10px 25px rgba(37,99,235,.3);
}

/* =========================================================
   CHAT SCREEN
========================================================= */

.chatHeader{
    height:65px;
    min-height:65px;

    display:flex;

    align-items:center;

    padding:0 12px;

    background:var(--card);

    border-bottom:1px solid var(--border);
}

.chatHeaderInfo{
    margin-left:10px;
}

.chatHeaderName{
    font-weight:700;
}

.online{
    color:var(--success);

    font-size:12px;
}

.messages{
    flex:1;

    overflow-y:auto;

    padding:18px 13px;

    background:
        radial-gradient(
            circle at top left,
            rgba(37,99,235,.05),
            transparent 35%
        ),
        var(--bg);
}

.messageRow{
    display:flex;

    margin-bottom:10px;
}

.messageRow.me{
    justify-content:flex-end;
}

.bubble{
    max-width:78%;

    padding:10px 13px;

    border-radius:17px;

    background:var(--incoming);

    box-shadow:
        0 1px 2px rgba(0,0,0,.04);

    word-wrap:break-word;
}

.me .bubble{
    background:var(--outgoing);

    color:var(--outgoing-text);

    border-bottom-right-radius:5px;
}

.messageTime{
    display:block;

    margin-top:4px;

    font-size:10px;

    opacity:.65;

    text-align:right;
}

.chatInputArea{
    padding:10px;

    background:var(--card);

    border-top:1px solid var(--border);

    display:flex;

    gap:8px;

    align-items:center;
}

.chatInput{
    flex:1;

    min-width:0;

    border:none;

    outline:none;

    background:var(--bg);

    color:var(--text);

    border-radius:22px;

    padding:12px 15px;

    font-size:15px;
}

.sendBtn{
    width:45px;
    height:45px;

    border:none;

    border-radius:50%;

    background:var(--primary);

    color:white;

    font-size:19px;
}

/* =========================================================
   CONTACTS
========================================================= */

.sectionTitle{
    padding:20px 18px 10px;

    font-size:14px;

    color:var(--muted);

    font-weight:700;

    text-transform:uppercase;
}

.contactItem{
    display:flex;

    align-items:center;

    padding:13px 18px;

    cursor:pointer;

    border-bottom:1px solid var(--border);
}

.contactItem:active{
    background:var(--bg);
}

.contactInfo{
    margin-left:13px;
}

.contactName{
    font-weight:700;
}

.contactStatus{
    color:var(--muted);

    font-size:13px;

    margin-top:3px;
}

/* =========================================================
   PROFILE
========================================================= */

.profile{
    padding:25px 18px;

    overflow-y:auto;
}

.profileTop{
    text-align:center;

    margin:20px 0 30px;
}

.profileAvatar{
    width:100px;
    height:100px;

    border-radius:50%;

    background:
        linear-gradient(
            135deg,
            var(--primary),
            var(--secondary)
        );

    color:white;

    display:flex;

    align-items:center;
    justify-content:center;

    font-size:38px;

    font-weight:800;

    margin:auto;
}

.profileName{
    margin-top:14px;

    font-size:24px;

    font-weight:800;
}

.profileUsername{
    color:var(--primary);

    margin-top:3px;
}

.profileEmail{
    color:var(--muted);

    margin-top:4px;
}

.setting{
    display:flex;

    align-items:center;

    padding:16px;

    background:var(--card);

    border-radius:15px;

    margin-bottom:10px;

    border:1px solid var(--border);

    cursor:pointer;
}

.settingIcon{
    width:40px;

    font-size:21px;
}

.settingInfo{
    flex:1;
}

.settingTitle{
    font-weight:700;
}

.settingDescription{
    color:var(--muted);

    font-size:12px;

    margin-top:3px;
}

.logout{
    color:var(--danger);
}

/* =========================================================
   MODAL
========================================================= */

.modal{
    position:fixed;

    inset:0;

    background:rgba(0,0,0,.5);

    display:none;

    align-items:flex-end;

    z-index:100;
}

.modal.show{
    display:flex;
}

.modalBox{
    width:100%;

    max-width:650px;

    margin:auto;

    background:var(--card);

    border-radius:25px 25px 0 0;

    padding:22px;

    animation:slideUp .25s ease;

    max-height:80vh;

    overflow-y:auto;
}

.modalTitle{
    font-size:21px;

    font-weight:800;

    margin-bottom:18px;
}

.closeBtn{
    float:right;

    border:none;

    background:var(--bg);

    color:var(--text);

    width:35px;
    height:35px;

    border-radius:50%;
}

/* =========================================================
   EMPTY
========================================================= */

.empty{
    min-height:200px;

    display:flex;

    flex-direction:column;

    align-items:center;

    justify-content:center;

    text-align:center;

    padding:30px;

    color:var(--muted);
}

.emptyIcon{
    font-size:60px;

    margin-bottom:15px;
}

/* =========================================================
   LOADING
========================================================= */

.loading{
    height:100%;

    min-height:200px;

    display:flex;

    align-items:center;

    justify-content:center;

    color:var(--muted);
}

/* =========================================================
   TOAST
========================================================= */

.toast{
    position:fixed;

    left:50%;

    bottom:90px;

    transform:
        translateX(-50%)
        translateY(20px);

    background:#0f172a;

    color:white;

    padding:12px 18px;

    border-radius:12px;

    opacity:0;

    pointer-events:none;

    transition:.25s;

    z-index:999;

    max-width:90%;

    text-align:center;
}

.toast.show{
    opacity:1;

    transform:
        translateX(-50%)
        translateY(0);
}

@media(min-width:651px){

    #app{
        box-shadow:
            0 0 50px rgba(0,0,0,.1);
    }

}

</style>
</head>

<body>

<div id="app">

<!-- =====================================================
     SPLASH
===================================================== -->

<section id="splashScreen" class="screen active">

    <div class="logo">💬</div>

    <div class="logoText">
        OroChat
    </div>

    <div class="tagline">
        Connect. Chat. Together.
    </div>

</section>


<!-- =====================================================
     LOGIN
===================================================== -->

<section id="loginScreen" class="screen auth">

    <div class="authLogo">
        <div class="smallLogo">💬</div>
    </div>

    <h1>Welcome back 👋</h1>

    <p class="authSubtitle">
        Sign in to continue to OroChat.
    </p>

    <div class="field">

        <label>Email</label>

        <input
            id="loginEmail"
            class="inputBox"
            type="email"
            autocomplete="email"
            placeholder="you@example.com">

    </div>

    <div class="field">

        <label>Password</label>

        <div class="inputWrap">

            <input
                id="loginPassword"
                class="inputBox passwordInput"
                type="password"
                autocomplete="current-password"
                placeholder="Your password">

            <button
                type="button"
                class="passwordToggle"
                onclick="togglePassword('loginPassword',this)">
                👁️
            </button>

        </div>

    </div>

    <div
        class="forgot"
        onclick="forgotPassword()">

        Forgot password?

    </div>

    <button
        id="loginButton"
        class="primaryBtn"
        onclick="login()">

        Login

    </button>

    <div class="divider">OR</div>

    <button
        class="googleBtn"
        onclick="googleLogin()">

        <span class="googleIcon">G</span>

        Continue with Google

    </button>

    <div class="authSwitch">

        Don't have an account?

        <span
            class="link"
            onclick="showScreen('registerScreen')">

            Register

        </span>

    </div>

</section>


<!-- =====================================================
     REGISTER
===================================================== -->

<section id="registerScreen" class="screen auth">

    <div class="authLogo">

        <div class="smallLogo">
            💬
        </div>

    </div>

    <h1>Create account</h1>

    <p class="authSubtitle">
        Join OroChat for free.
    </p>

    <div class="field">

        <label>Full name</label>

        <input
            id="registerName"
            class="inputBox"
            type="text"
            autocomplete="name"
            placeholder="Your full name">

    </div>

    <div class="field">

        <label>Username</label>

        <input
            id="registerUsername"
            class="inputBox"
            type="text"
            autocomplete="username"
            placeholder="@username">

    </div>

    <div class="field">

        <label>Email</label>

        <input
            id="registerEmail"
            class="inputBox"
            type="email"
            autocomplete="email"
            placeholder="you@example.com">

    </div>

    <div class="field">

        <label>Password</label>

        <div class="inputWrap">

            <input
                id="registerPassword"
                class="inputBox passwordInput"
                type="password"
                autocomplete="new-password"
                placeholder="Create password">

            <button
                type="button"
                class="passwordToggle"
                onclick="togglePassword('registerPassword',this)">
                👁️
            </button>

        </div>

    </div>

    <div class="field">

        <label>Confirm password</label>

        <div class="inputWrap">

            <input
                id="registerConfirm"
                class="inputBox passwordInput"
                type="password"
                autocomplete="new-password"
                placeholder="Repeat password">

            <button
                type="button"
                class="passwordToggle"
                onclick="togglePassword('registerConfirm',this)">
                👁️
            </button>

        </div>

    </div>

    <button
        id="registerButton"
        class="primaryBtn"
        onclick="register()">

        Create Account

    </button>

    <div class="divider">OR</div>

    <button
        class="googleBtn"
        onclick="googleLogin()">

        <span class="googleIcon">G</span>

        Sign up with Google

    </button>

    <div class="authSwitch">

        Already have an account?

        <span
            class="link"
            onclick="showScreen('loginScreen')">

            Login

        </span>

    </div>

</section>


<!-- =====================================================
     HOME
===================================================== -->

<section id="homeScreen" class="screen">

    <header class="topBar">

        <div class="topTitle">
            OroChat
        </div>

        <div class="topActions">

            <button
                class="iconBtn"
                onclick="focusHomeSearch()">
                🔍
            </button>

            <button
                class="iconBtn"
                onclick="showToast('More options coming soon')">
                ⋮
            </button>

        </div>

    </header>

    <div class="searchArea">

        <input
            id="homeSearch"
            class="search"
            type="search"
            placeholder="Search conversations..."
            oninput="searchChats()">

    </div>

    <div
        id="chatList"
        class="content">

        <div class="loading">
            Loading conversations...
        </div>

    </div>

    <button
        class="fab"
        onclick="openNewChat()">

        ✎

    </button>

    <nav class="bottomNav">

        <button
            class="navItem active"
            onclick="switchMain('homeScreen',this)">

            <span class="navIcon">💬</span>

            Chats

        </button>

        <button
            class="navItem"
            onclick="switchMain('contactsScreen',this)">

            <span class="navIcon">👥</span>

            Contacts

        </button>

        <button
            class="navItem"
            onclick="switchMain('profileScreen',this)">

            <span class="navIcon">👤</span>

            Profile

        </button>

    </nav>

</section>


<!-- =====================================================
     CONTACTS
===================================================== -->

<section id="contactsScreen" class="screen">

    <header class="topBar">

        <div class="topTitle">
            Contacts
        </div>

        <button
            class="iconBtn"
            onclick="openNewChat()">

            ➕

        </button>

    </header>

    <div
        id="contactList"
        class="content">

        <div class="loading">
            Loading contacts...
        </div>

    </div>

    <nav class="bottomNav">

        <button
            class="navItem"
            onclick="switchMain('homeScreen',this)">

            <span class="navIcon">💬</span>

            Chats

        </button>

        <button class="navItem active">

            <span class="navIcon">👥</span>

            Contacts

        </button>

        <button
            class="navItem"
            onclick="switchMain('profileScreen',this)">

            <span class="navIcon">👤</span>

            Profile

        </button>

    </nav>

</section>


<!-- =====================================================
     PROFILE
===================================================== -->

<section id="profileScreen" class="screen">

    <header class="topBar">

        <div class="topTitle">
            Profile
        </div>

        <button
            class="iconBtn"
            onclick="showToast('Profile editing coming soon')">

            ✏️

        </button>

    </header>

    <div class="profile content">

        <div class="profileTop">

            <div
                id="profileAvatar"
                class="profileAvatar">
                E
            </div>

            <div
                id="profileName"
                class="profileName">
                Loading...
            </div>

            <div
                id="profileUsername"
                class="profileUsername">
                @username
            </div>

            <div
                id="profileEmail"
                class="profileEmail">
                email
            </div>

        </div>

        <div
            class="setting"
            onclick="toggleDarkMode()">

            <div class="settingIcon">🌙</div>

            <div class="settingInfo">

                <div class="settingTitle">
                    Dark Mode
                </div>

                <div class="settingDescription">
                    Change the appearance
                </div>

            </div>

            <div>→</div>

        </div>

        <div
            class="setting"
            onclick="showToast('Notification settings coming soon')">

            <div class="settingIcon">🔔</div>

            <div class="settingInfo">

                <div class="settingTitle">
                    Notifications
                </div>

                <div class="settingDescription">
                    Manage notifications
                </div>

            </div>

            <div>→</div>

        </div>

        <div
            class="setting"
            onclick="showToast('Privacy settings coming soon')">

            <div class="settingIcon">🔐</div>

            <div class="settingInfo">

                <div class="settingTitle">
                    Privacy
                </div>

                <div class="settingDescription">
                    Control your privacy
                </div>

            </div>

            <div>→</div>

        </div>

        <div
            class="setting"
            onclick="showToast('Premium features coming soon')">

            <div class="settingIcon">⭐</div>

            <div class="settingInfo">

                <div class="settingTitle">
                    OroChat Premium
                </div>

                <div class="settingDescription">
                    Unlock premium features
                </div>

            </div>

            <div>→</div>

        </div>

        <div
            class="setting logout"
            onclick="logout()">

            <div class="settingIcon">🚪</div>

            <div class="settingInfo">

                <div class="settingTitle">
                    Logout
                </div>

                <div class="settingDescription">
                    Sign out of OroChat
                </div>

            </div>

        </div>

    </div>

</section>


<!-- =====================================================
     CHAT
===================================================== -->

<section id="chatScreen" class="screen">

    <header class="chatHeader">

        <button
            class="iconBtn"
            onclick="closeChat()">

            ←

        </button>

        <div
            id="chatAvatar"
            class="avatar">

            U

        </div>

        <div class="chatHeaderInfo">

            <div
                id="chatName"
                class="chatHeaderName">

                User

            </div>

            <div class="online">
                OroChat
            </div>

        </div>

        <div style="margin-left:auto">

            <button
                class="iconBtn"
                onclick="showToast('Voice calling coming soon')">
                📞
            </button>

            <button
                class="iconBtn"
                onclick="showToast('Video calling coming soon')">
                📹
            </button>

        </div>

    </header>

    <div
        id="messages"
        class="messages">
    </div>

    <div class="chatInputArea">

        <button
            class="iconBtn"
            onclick="showEmoji()">

            😊

        </button>

        <input
            id="messageInput"
            class="chatInput"
            type="text"
            placeholder="Message..."
            onkeydown="handleMessageKey(event)">

        <button
            class="sendBtn"
            onclick="sendMessage()">

            ➤

        </button>

    </div>

</section>


<!-- =====================================================
     NEW CHAT MODAL
===================================================== -->

<div
    id="newChatModal"
    class="modal">

    <div class="modalBox">

        <button
            class="closeBtn"
            onclick="closeNewChat()">

            ×

        </button>

        <div class="modalTitle">
            New conversation
        </div>

        <input
            id="newChatSearch"
            class="inputBox"
            placeholder="Search people..."
            oninput="searchContacts()">

        <div
            id="newChatResults"
            style="margin-top:15px">

        </div>

    </div>

</div>


<div id="toast" class="toast"></div>

</div>


<!-- =========================================================
     FIREBASE + JAVASCRIPT
========================================================= -->

<script type="module">

/* =========================================================
   FIREBASE IMPORTS
========================================================= */

import {
    initializeApp
}
from "https://www.gstatic.com/firebasejs/12.17.1/firebase-app.js";


import {
    getAuth,
    createUserWithEmailAndPassword,
    signInWithEmailAndPassword,
    signOut,
    onAuthStateChanged,
    sendPasswordResetEmail,
    GoogleAuthProvider,
    signInWithPopup,
    updateProfile
}
from "https://www.gstatic.com/firebasejs/12.17.1/firebase-auth.js";


import {
    getFirestore,
    doc,
    setDoc,
    getDoc,
    collection,
    addDoc,
    query,
    orderBy,
    onSnapshot,
    serverTimestamp,
    getDocs
}
from "https://www.gstatic.com/firebasejs/12.17.1/firebase-firestore.js";


/* =========================================================
   FIREBASE CONFIGURATION
========================================================= */

const firebaseConfig = {

    apiKey:
        "AIzaSyDVPx9GItHrY4RMEkuvQ9EyAnj6lZisafY",

    authDomain:
        "orochat-7a420.firebaseapp.com",

    projectId:
        "orochat-7a420",

    storageBucket:
        "orochat-7a420.firebasestorage.app",

    messagingSenderId:
        "305593144262",

    appId:
        "1:305593144262:web:932bff0034495829c158c7"

};


/* =========================================================
   INITIALIZE
========================================================= */

const app =
    initializeApp(firebaseConfig);

const auth =
    getAuth(app);

const db =
    getFirestore(app);

const googleProvider =
    new GoogleAuthProvider();


/* =========================================================
   APP STATE
========================================================= */

let currentUser = null;

let currentChatUser = null;

let unsubscribeMessages = null;

let allUsers = [];

let allChats = [];

let toastTimer = null;


/* =========================================================
   SCREEN FUNCTIONS
========================================================= */

window.showScreen = function(id){

    document
        .querySelectorAll(".screen")
        .forEach(screen => {

            screen.classList.remove("active");

        });


    const screen =
        document.getElementById(id);


    if(screen){

        screen.classList.add("active");

    }

};


/* =========================================================
   MAIN NAVIGATION
========================================================= */

window.switchMain = async function(id,button){

    showScreen(id);


    if(id === "contactsScreen"){

        await renderContacts();

    }


    if(id === "profileScreen"){

        await loadProfile();

    }


    document
        .querySelectorAll(".bottomNav .navItem")
        .forEach(item => {

            item.classList.remove("active");

        });


    if(button){

        button.classList.add("active");

    }

};


/* =========================================================
   PASSWORD TOGGLE
========================================================= */

window.togglePassword =
function(inputId,button){

    const input =
        document.getElementById(inputId);


    if(!input){

        return;

    }


    if(input.type === "password"){

        input.type = "text";

        button.textContent = "🙈";

    }
    else{

        input.type = "password";

        button.textContent = "👁️";

    }

};


/* =========================================================
   TOAST
========================================================= */

window.showToast = function(message){

    const toast =
        document.getElementById("toast");


    toast.textContent = message;

    toast.classList.add("show");


    clearTimeout(toastTimer);


    toastTimer =
        setTimeout(() => {

            toast.classList.remove("show");

        },3000);

};


/* =========================================================
   SAFE HTML
========================================================= */

function escapeHTML(value){

    return String(value ?? "")
        .replaceAll("&","&amp;")
        .replaceAll("<","&lt;")
        .replaceAll(">","&gt;")
        .replaceAll('"',"&quot;")
        .replaceAll("'","&#039;");

}


/* =========================================================
   FIREBASE ERROR
========================================================= */

function firebaseError(error){

    console.error(
        "Firebase error:",
        error
    );


    const code =
        error?.code || "";


    const messages = {

        "auth/email-already-in-use":
            "This email is already registered.",

        "auth/invalid-email":
            "Please enter a valid email.",

        "auth/weak-password":
            "Password must be at least 6 characters.",

        "auth/invalid-credential":
            "Incorrect email or password.",

        "auth/user-not-found":
            "No account was found.",

        "auth/wrong-password":
            "Incorrect password.",

        "auth/network-request-failed":
            "Network error. Check your internet.",

        "auth/popup-closed-by-user":
            "Google sign-in was cancelled.",

        "auth/popup-blocked":
            "Your browser blocked Google sign-in.",

        "auth/operation-not-allowed":
            "This sign-in method is not enabled in Firebase.",

        "permission-denied":
            "Firestore permission denied. Check Firestore Rules.",

        "failed-precondition":
            "Firestore configuration/index problem.",

        "unavailable":
            "Firebase is temporarily unavailable."

    };


    showToast(
        messages[code] ||
        error?.message ||
        "Something went wrong."
    );

}


/* =========================================================
   REGISTER
========================================================= */

window.register = async function(){

    const name =
        document
        .getElementById("registerName")
        .value
        .trim();


    const username =
        document
        .getElementById("registerUsername")
        .value
        .trim();


    const email =
        document
        .getElementById("registerEmail")
        .value
        .trim()
        .toLowerCase();


    const password =
        document
        .getElementById("registerPassword")
        .value;


    const confirm =
        document
        .getElementById("registerConfirm")
        .value;


    if(
        !name ||
        !username ||
        !email ||
        !password ||
        !confirm
    ){

        showToast(
            "Please complete all fields."
        );

        return;

    }


    if(password.length < 6){

        showToast(
            "Password must be at least 6 characters."
        );

        return;

    }


    if(password !== confirm){

        showToast(
            "Passwords do not match."
        );

        return;

    }


    try{

        const credential =
            await createUserWithEmailAndPassword(
                auth,
                email,
                password
            );


        const user =
            credential.user;


        const cleanUsername =
            username.startsWith("@")
            ? username
            : "@" + username;


        await updateProfile(
            user,
            {
                displayName:name
            }
        );


        await setDoc(
            doc(
                db,
                "users",
                user.uid
            ),
            {

                uid:user.uid,

                name:name,

                username:cleanUsername,

                email:user.email,

                photoURL:
                    user.photoURL || "",

                createdAt:
                    serverTimestamp(),

                lastSeen:
                    serverTimestamp()

            }
        );


        clearRegisterForm();


        showToast(
            "Account created successfully 🎉"
        );

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   CLEAR REGISTER
========================================================= */

function clearRegisterForm(){

    document
        .getElementById("registerName")
        .value = "";

    document
        .getElementById("registerUsername")
        .value = "";

    document
        .getElementById("registerEmail")
        .value = "";

    document
        .getElementById("registerPassword")
        .value = "";

    document
        .getElementById("registerConfirm")
        .value = "";

}


/* =========================================================
   LOGIN
========================================================= */

window.login = async function(){

    const email =
        document
        .getElementById("loginEmail")
        .value
        .trim()
        .toLowerCase();


    const password =
        document
        .getElementById("loginPassword")
        .value;


    if(!email || !password){

        showToast(
            "Enter your email and password."
        );

        return;

    }


    try{

        await signInWithEmailAndPassword(
            auth,
            email,
            password
        );


        document
            .getElementById("loginPassword")
            .value = "";


        showToast(
            "Login successful 👋"
        );

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   GOOGLE LOGIN
========================================================= */

window.googleLogin =
async function(){

    try{

        const result =
            await signInWithPopup(
                auth,
                googleProvider
            );


        const user =
            result.user;


        const userRef =
            doc(
                db,
                "users",
                user.uid
            );


        const existing =
            await getDoc(userRef);


        if(!existing.exists()){

            let base =
                user.displayName ||
                user.email?.split("@")[0] ||
                "user";


            base =
                base
                .toLowerCase()
                .replace(
                    /[^a-z0-9_]/g,
                    ""
                );


            if(!base){

                base = "user";

            }


            await setDoc(
                userRef,
                {

                    uid:user.uid,

                    name:
                        user.displayName ||
                        "OroChat User",

                    username:
                        "@" + base,

                    email:
                        user.email || "",

                    photoURL:
                        user.photoURL || "",

                    createdAt:
                        serverTimestamp(),

                    lastSeen:
                        serverTimestamp()

                }
            );

        }


        showToast(
            "Google sign-in successful 🎉"
        );

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   PASSWORD RESET
========================================================= */

window.forgotPassword =
async function(){

    const email =
        document
        .getElementById("loginEmail")
        .value
        .trim()
        .toLowerCase();


    if(!email){

        showToast(
            "Enter your email first."
        );

        return;

    }


    try{

        await sendPasswordResetEmail(
            auth,
            email
        );


        showToast(
            "Password reset email sent."
        );

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   LOGOUT
========================================================= */

window.logout =
async function(){

    try{

        if(unsubscribeMessages){

            unsubscribeMessages();

            unsubscribeMessages = null;

        }


        await signOut(auth);


        currentUser = null;

        currentChatUser = null;


        showScreen(
            "loginScreen"
        );


        showToast(
            "You have been logged out."
        );

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   AUTH STATE
========================================================= */

onAuthStateChanged(
    auth,

    async user => {

        if(user){

            currentUser = user;


            try{

                await saveUserProfile();

                await loadProfile();

                showScreen(
                    "homeScreen"
                );

                await loadUsers();

                await renderChats();

            }
            catch(error){

                console.error(error);

                showToast(
                    "Could not load your OroChat data."
                );

            }

        }
        else{

            currentUser = null;

            showScreen(
                "loginScreen"
            );

        }

    }

);


/* =========================================================
   SAVE PROFILE
========================================================= */

async function saveUserProfile(){

    if(!currentUser){

        return;

    }


    const ref =
        doc(
            db,
            "users",
            currentUser.uid
        );


    const snapshot =
        await getDoc(ref);


    if(!snapshot.exists()){

        await setDoc(
            ref,
            {

                uid:
                    currentUser.uid,

                name:
                    currentUser.displayName ||
                    "User",

                username:
                    "@" +
                    (
                        currentUser.email
                        ?.split("@")[0] ||
                        "user"
                    ),

                email:
                    currentUser.email ||
                    "",

                photoURL:
                    currentUser.photoURL ||
                    "",

                createdAt:
                    serverTimestamp(),

                lastSeen:
                    serverTimestamp()

            }
        );

    }
    else{

        await setDoc(
            ref,
            {

                lastSeen:
                    serverTimestamp()

            },
            {
                merge:true
            }
        );

    }

}


/* =========================================================
   LOAD PROFILE
========================================================= */

async function loadProfile(){

    if(!currentUser){

        return;

    }


    try{

        const snapshot =
            await getDoc(
                doc(
                    db,
                    "users",
                    currentUser.uid
                )
            );


        if(!snapshot.exists()){

            return;

        }


        const data =
            snapshot.data();


        const name =
            data.name ||
            currentUser.displayName ||
            "User";


        document
            .getElementById("profileName")
            .textContent =
            name;


        document
            .getElementById("profileUsername")
            .textContent =
            data.username || "";


        document
            .getElementById("profileEmail")
            .textContent =
            data.email ||
            currentUser.email ||
            "";


        document
            .getElementById("profileAvatar")
            .textContent =
            name
            .charAt(0)
            .toUpperCase();

    }
    catch(error){

        firebaseError(error);

    }

}


/* =========================================================
   LOAD ALL USERS
========================================================= */

async function loadUsers(){

    if(!currentUser){

        return;

    }


    try{

        const snapshot =
            await getDocs(
                collection(
                    db,
                    "users"
                )
            );


        allUsers = [];


        snapshot.forEach(
            userDocument => {

                const data =
                    userDocument.data();


                if(
                    data.uid ===
                    currentUser.uid
                ){

                    return;

                }


                const name =
                    data.name ||
                    "User";


                allUsers.push({

                    id:
                        data.uid ||
                        userDocument.id,

                    name:name,

                    username:
                        data.username ||
                        "",

                    email:
                        data.email ||
                        "",

                    avatar:
                        name
                        .charAt(0)
                        .toUpperCase()

                });

            }
        );


    }
    catch(error){

        firebaseError(error);

    }

}


/* =========================================================
   CONTACTS
========================================================= */

async function renderContacts(){

    const container =
        document.getElementById(
            "contactList"
        );


    container.innerHTML = `
        <div class="loading">
            Loading contacts...
        </div>
    `;


    await loadUsers();


    if(!allUsers.length){

        container.innerHTML = `

            <div class="empty">

                <div class="emptyIcon">
                    👥
                </div>

                <h3>
                    No other users yet
                </h3>

                <p>
                    Create another OroChat account
                    to test messaging.
                </p>

            </div>

        `;

        return;

    }


    let html = `

        <div class="sectionTitle">
            OroChat users
        </div>

    `;


    allUsers.forEach(user => {

        html += `

            <div
                class="contactItem"
                data-user-id="${escapeHTML(user.id)}">

                <div class="avatar">
                    ${escapeHTML(user.avatar)}
                </div>

                <div class="contactInfo">

                    <div class="contactName">
                        ${escapeHTML(user.name)}
                    </div>

                    <div class="contactStatus">
                        ${escapeHTML(user.username)}
                    </div>

                </div>

            </div>

        `;

    });


    container.innerHTML =
        html;


    container
        .querySelectorAll(".contactItem")
        .forEach(item => {

            item.addEventListener(
                "click",
                () => {

                    openChat(
                        item.dataset.userId
                    );

                }
            );

        });

}


/* =========================================================
   CHAT ID
========================================================= */

function getChatId(uid1,uid2){

    return [
        uid1,
        uid2
    ]
    .sort()
    .join("_");

}


/* =========================================================
   OPEN CHAT
========================================================= */

window.openChat =
async function(userId){

    if(!currentUser){

        return;

    }


    if(
        !userId ||
        userId === currentUser.uid
    ){

        return;

    }


    try{

        const snapshot =
            await getDoc(
                doc(
                    db,
                    "users",
                    userId
                )
            );


        if(!snapshot.exists()){

            showToast(
                "User could not be found."
            );

            return;

        }


        const data =
            snapshot.data();


        currentChatUser = {

            id:
                data.uid ||
                snapshot.id,

            name:
                data.name ||
                "User",

            username:
                data.username ||
                "",

            avatar:
                (
                    data.name ||
                    "U"
                )
                .charAt(0)
                .toUpperCase()

        };


        document
            .getElementById("chatName")
            .textContent =
            currentChatUser.name;


        document
            .getElementById("chatAvatar")
            .textContent =
            currentChatUser.avatar;


        showScreen(
            "chatScreen"
        );


        document
            .getElementById("messageInput")
            .focus();


        listenForMessages();

    }
    catch(error){

        firebaseError(error);

    }

};


/* =========================================================
   CLOSE CHAT
========================================================= */

window.closeChat =
function(){

    if(unsubscribeMessages){

        unsubscribeMessages();

        unsubscribeMessages = null;

    }


    currentChatUser = null;


    showScreen(
        "homeScreen"
    );


    renderChats();

};


/* =========================================================
   LISTEN FOR MESSAGES
========================================================= */

function listenForMessages(){

    if(!currentUser || !currentChatUser){

        return;

    }


    if(unsubscribeMessages){

        unsubscribeMessages();

        unsubscribeMessages = null;

    }


    const chatId =
        getChatId(
            currentUser.uid,
            currentChatUser.id
        );


    const messagesRef =
        collection(
            db,
            "chats",
            chatId,
            "messages"
        );


    const messagesQuery =
        query(
            messagesRef,
            orderBy(
                "createdAt",
                "asc"
            )
        );


    unsubscribeMessages =
        onSnapshot(
            messagesQuery,

            snapshot => {

                const container =
                    document.getElementById(
                        "messages"
                    );


                if(snapshot.empty){

                    container.innerHTML = `

                        <div class="empty">

                            <div class="emptyIcon">
                                💬
                            </div>

                            <p>
                                Start the conversation.
                            </p>

                        </div>

                    `;

                    return;

                }


                container.innerHTML = "";


                snapshot.forEach(
                    messageDoc => {

                        const data =
                            messageDoc.data();


                        const mine =
                            data.senderId ===
                            currentUser.uid;


                        const row =
                            document.createElement(
                                "div"
                            );


                        row.className =
                            "messageRow" +
                            (
                                mine
                                ? " me"
                                : ""
                            );


                        const bubble =
                            document.createElement(
                                "div"
                            );


                        bubble.className =
                            "bubble";


                        const text =
                            document.createElement(
                                "div"
                            );


                        text.textContent =
                            data.text || "";


                        const time =
                            document.createElement(
                                "span"
                            );


                        time.className =
                            "messageTime";


                        time.textContent =
                            formatMessageTime(
                                data.createdAt
                            );


                        bubble.appendChild(text);

                        bubble.appendChild(time);

                        row.appendChild(bubble);

                        container.appendChild(row);

                    }
                );


                container.scrollTop =
                    container.scrollHeight;

            },

            error => {

                console.error(
                    "Message listener:",
                    error
                );

                showToast(
                    "Could not load messages."
                );

            }

        );

}


/* =========================================================
   SEND MESSAGE
========================================================= */

window.sendMessage =
async function(){

    if(
        !currentUser ||
        !currentChatUser
    ){

        return;

    }


    const input =
        document.getElementById(
            "messageInput"
        );


    const text =
        input.value.trim();


    if(!text){

        return;

    }


    input.disabled = true;


    try{

        const chatId =
            getChatId(
                currentUser.uid,
                currentChatUser.id
            );


        const messagesRef =
            collection(
                db,
                "chats",
                chatId,
                "messages"
            );


        await addDoc(
            messagesRef,
            {

                text:text,

                senderId:
                    currentUser.uid,

                receiverId:
                    currentChatUser.id,

                createdAt:
                    serverTimestamp()

            }
        );


        await setDoc(
            doc(
                db,
                "chats",
                chatId
            ),
            {

                participants:[
                    currentUser.uid,
                    currentChatUser.id
                ],

                lastMessage:text,

                lastSenderId:
                    currentUser.uid,

                updatedAt:
                    serverTimestamp()

            },
            {
                merge:true
            }
        );


        input.value = "";

    }
    catch(error){

        firebaseError(error);

    }
    finally{

        input.disabled = false;

        input.focus();

    }

};


/* =========================================================
   ENTER TO SEND
========================================================= */

window.handleMessageKey =
function(event){

    if(
        event.key === "Enter" &&
        !event.shiftKey
    ){

        event.preventDefault();

        sendMessage();

    }

};


/* =========================================================
   MESSAGE TIME
========================================================= */

function formatMessageTime(timestamp){

    if(!timestamp){

        return "sending...";

    }


    try{

        const date =
            timestamp.toDate();


        return date.toLocaleTimeString(
            [],
            {
                hour:"2-digit",
                minute:"2-digit"
            }
        );

    }
    catch{

        return "";

    }

}


/* =========================================================
   RENDER CHATS
========================================================= */

async function renderChats(){

    const container =
        document.getElementById(
            "chatList"
        );


    if(!currentUser){

        return;

    }


    container.innerHTML = `

        <div class="loading">
            Loading conversations...
        </div>

    `;


    try{

        const chatsSnapshot =
            await getDocs(
                collection(
                    db,
                    "chats"
                )
            );


        const chats = [];


        chatsSnapshot.forEach(
            chatDocument => {

                const data =
                    chatDocument.data();


                if(
                    !Array.isArray(
                        data.participants
                    )
                ){

                    return;

                }


                if(
                    !data.participants.includes(
                        currentUser.uid
                    )
                ){

                    return;

                }


                const otherId =
                    data.participants.find(
                        id =>
                        id !== currentUser.uid
                    );


                if(!otherId){

                    return;

                }


                chats.push({

                    id:
                        chatDocument.id,

                    otherId:

                        otherId,

                    lastMessage:
                        data.lastMessage ||
                        "",

                    updatedAt:
                        data.updatedAt || null

                });

            }
        );


        allChats = chats;


        if(!chats.length){

            container.innerHTML = `

                <div class="empty">

                    <div class="emptyIcon">
                        💬
                    </div>

                    <h3>
                        No conversations
                    </h3>

                    <p>
                        Tap ✎ to start a new chat.
                    </p>

                </div>

            `;

            return;

        }


        const userMap = new Map();

        allUsers.forEach(
            user => {

                userMap.set(
                    user.id,
                    user
                );

            }
        );


        let html = "";


        for(const chat of chats){

            let other =
                userMap.get(
                    chat.otherId
                );


            if(!other){

                try{

                    const userSnapshot =
                        await getDoc(
                            doc(
                                db,
                                "users",
                                chat.otherId
                            )
                        );


                    if(userSnapshot.exists()){

                        const data =
                            userSnapshot.data();


                        const name =
                            data.name ||
                            "User";


                        other = {

                            id:
                                chat.otherId,

                            name:name,

                            username:
                                data.username ||
                                "",

                            avatar:
                                name
                                .charAt(0)
                                .toUpperCase()

                        };

                    }

                }
                catch{

                    continue;

                }

            }


            if(!other){

                continue;

            }


            html += `

                <div
                    class="chatItem"
                    data-user-id="${escapeHTML(other.id)}">

                    <div class="avatar">
                        ${escapeHTML(other.avatar)}
                    </div>

                    <div class="chatInfo">

                        <div class="chatTop">

                            <div class="chatName">
                                ${escapeHTML(other.name)}
                            </div>

                            <div class="chatTime">
                                ${formatMessageTime(chat.updatedAt)}
                            </div>

                        </div>

                        <div class="lastMessage">
                            ${escapeHTML(chat.lastMessage || "Start chatting")}
                        </div>

                    </div>

                </div>

            `;

        }


        if(!html){

            container.innerHTML = `

                <div class="empty">

                    <div class="emptyIcon">
                        💬
                    </div>

                    <p>
                        No conversations yet.
                    </p>

                </div>

            `;

            return;

        }


        container.innerHTML =
            html;


        container
            .querySelectorAll(".chatItem")
            .forEach(item => {

                item.addEventListener(
                    "click",
                    () => {

                        openChat(
                            item.dataset.userId
                        );

                    }
                );

            });

    }
    catch(error){

        firebaseError(error);

        container.innerHTML = `

            <div class="empty">

                <div class="emptyIcon">
                    ⚠️
                </div>

                <h3>
                    Could not load chats
                </h3>

                <p>
                    Check your Firestore rules.
                </p>

            </div>

        `;

    }

}


/* =========================================================
   SEARCH CHATS
========================================================= */

window.searchChats =
function(){

    const value =
        document
        .getElementById("homeSearch")
        .value
        .trim()
        .toLowerCase();


    const items =
        document.querySelectorAll(
            "#chatList .chatItem"
        );


    items.forEach(item => {

        const text =
            item.textContent
            .toLowerCase();


        item.style.display =
            text.includes(value)
            ? "flex"
            : "none";

    });

};


/* =========================================================
   HOME SEARCH
========================================================= */

window.focusHomeSearch =
function(){

    const input =
        document.getElementById(
            "homeSearch"
        );


    input.focus();

};


/* =========================================================
   NEW CHAT MODAL
========================================================= */

window.openNewChat =
function(){

    document
        .getElementById(
            "newChatModal"
        )
        .classList.add("show");


    document
        .getElementById(
            "newChatSearch"
        )
        .value = "";


    renderNewChatResults();

};


window.closeNewChat =
function(){

    document
        .getElementById(
            "newChatModal"
        )
        .classList.remove("show");

};


/* =========================================================
   SEARCH CONTACTS
========================================================= */

window.searchContacts =
function(){

    renderNewChatResults();

};


/* =========================================================
   NEW CHAT RESULTS
========================================================= */

function renderNewChatResults(){

    const container =
        document.getElementById(
            "newChatResults"
        );


    const input =
        document.getElementById(
            "newChatSearch"
        );


    const search =
        input.value
        .trim()
        .toLowerCase();


    let users =
        allUsers;


    if(search){

        users =
            users.filter(
                user => {

                    return (

                        user.name
                        .toLowerCase()
                        .includes(search)

                        ||

                        user.username
                        .toLowerCase()
                        .includes(search)

                        ||

                        user.email
                        .toLowerCase()
                        .includes(search)

                    );

                }
            );

    }


    if(!users.length){

        container.innerHTML = `

            <div class="empty">

                <div class="emptyIcon">
                    👤
                </div>

                <p>
                    No users found.
                </p>

            </div>

        `;

        return;

    }


    let html = "";


    users.forEach(user => {

        html += `

            <div
                class="contactItem"
                data-user-id="${escapeHTML(user.id)}">

                <div class="avatar">
                    ${escapeHTML(user.avatar)}
                </div>

                <div class="contactInfo">

                    <div class="contactName">
                        ${escapeHTML(user.name)}
                    </div>

                    <div class="contactStatus">
                        ${escapeHTML(user.username)}
                    </div>

                </div>

            </div>

        `;

    });


    container.innerHTML =
        html;


    container
        .querySelectorAll(".contactItem")
        .forEach(item => {

            item.addEventListener(
                "click",
                () => {

                    closeNewChat();

                    openChat(
                        item.dataset.userId
                    );

                }
            );

        });

}


/* =========================================================
   EMOJI
========================================================= */

window.showEmoji =
function(){

    const input =
        document.getElementById(
            "messageInput"
        );


    input.value += " 😊";

    input.focus();

};


/* =========================================================
   DARK MODE
========================================================= */

window.toggleDarkMode =
function(){

    document.body.classList.toggle(
        "dark"
    );


    localStorage.setItem(
        "orochatDarkMode",
        document.body.classList.contains(
            "dark"
        )
        ? "true"
        : "false"
    );

};


/* =========================================================
   LOAD DARK MODE
========================================================= */

if(
    localStorage.getItem(
        "orochatDarkMode"
    ) === "true"
){

    document.body.classList.add(
        "dark"
    );

}


/* =========================================================
   SPLASH TIMER
========================================================= */

setTimeout(
    () => {

        if(!currentUser){

            showScreen(
                "loginScreen"
            );

        }

    },
    1800
);

</script>

</body>
</html>