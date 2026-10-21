# LuminaGear — Full-Stack Deployment & Project Architecture Capstone

A production-ready, modular E-Commerce Single Page Application (SPA) built for the **Full-Stack Deployment & Project Architecture** capstone project.

## ✨ Key Features Implemented
- **Modular Frontend Architecture:** Clean separation between state (`Store`), routing (`Router`), UI components (`UI`), and page views (`Views`).
- **Client-Side Routing:** Seamless navigation (`#/`, `#/shop`, `#/product/:id`, `#/saved`, `#/checkout`, `#/architecture`) without page reloads.
- **Asset & Performance Optimization:** Responsive WebP imagery with `loading="lazy"`, `decoding="async"`, and DNS preconnect hints.
- **Persistent State:** Shopping cart, wishlist, and dark/light theme preferences saved automatically in `localStorage`.

## 🚀 Live Deployment Instructions
1. Upload `index.html`, `style.css`, `app.js`, and `README.md` directly to a GitHub repository.
2. Connect the repository to **Vercel**, **Netlify**, or **Render** (Static Site).
3. Leave the build command blank and set the publish directory to `/` (root).