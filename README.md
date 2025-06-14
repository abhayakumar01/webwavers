# WebWeavers Blogs

Welcome to **WebWeavers Blogs** – a community-driven blogging hub built for WebWeavers users to create, explore, and connect through shared content and communities.

## 🌐 Live Preview

> _Coming soon..._ (Add your deployment link here, e.g., Netlify, GitHub Pages, etc.)

---

## 🚀 Features

- 🔐 **Authentication Redirect**: Users must be signed in (via `localStorage`) to access the app.
- 🧭 **Navigation**: Clean header navigation with links to Home, Feed, Create, and Communities.
- 📝 **Blog Home Page**: Static homepage with banner and welcome message.
- 🔓 **Logout Functionality**: Client-side logout clears session and redirects to the login page.

---

## 📁 Project Structure

webweavers-blogs/
│
├── index.html # Main homepage
├── feed.html # (Future) Blog feed page
├── create.html # (Future) Blog post creation page
├── community.html # (Future) Community listings
├── signin.html # Sign-in page
│
├── css/
│ └── style.css # Project styles
│
├── assets/
│ └── Home-banner.png # Homepage banner image
│
└── README.md # You're here!



## 🛠️ How to Run Locally

1. Clone or download this repository.
2. Make sure all files (HTML, CSS, assets) are in place.
3. Open `index.html` in a web browser.
4. Ensure `localStorage` has a `user` item set, or you’ll be redirected to `signin.html`.

```js
// Open DevTools and run this to simulate a login:
localStorage.setItem("user", "exampleUser");
