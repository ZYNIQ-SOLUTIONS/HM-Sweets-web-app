# HM Sweets — Artisanal UAE Pastry Web Application

A luxury, mobile-first web storefront and ordering experience for **HM Sweets** (@byhm.sweets), handcrafted with love in the UAE.

---

## ✨ Features

- **Luxury Brand Experience**: Warm burgundy (`#5E0B15`) & cream (`#FAE5D2`) palette with custom typography (*Bodoni Moda* & *Figtree*).
- **Interactive 3D Dessert Stage**: Real-time rotating Three.js dessert models with touch momentum and responsive lights.
- **Instagram / TikTok Multi-Figure Carousels**: Seamless visual toggles between dessert presentation styles (*Slice* ↔ *Sharing tub*).
- **My Sweet Box Builder**:
  - Direct piece quantity selection.
  - Custom baker notes (e.g., custom greetings or box inscriptions).
  - Live illuminating counter bulb on the persistent bottom navigation dock.
- **UAE-Tailored Checkout Flow**:
  - Full client contact capture with UAE phone formatting.
  - Interactive Leaflet map pinning for exact delivery location.
  - One-tap WhatsApp order payload generator pre-formatted for `@byhm.sweets`.
- **Zero-Dependency Architecture**: Entirely self-contained static web application with embedded high-resolution assets.

---

## 🚀 Netlify Deployment

This project is pre-configured for instant zero-configuration deployment to Netlify:

### Method 1: Git Integration (Recommended)
1. Push this repository to GitHub, GitLab, or Bitbucket.
2. Log into [Netlify](https://app.netlify.com) and click **"Add new site"** > **"Import an existing project"**.
3. Select your repository.
4. Netlify will automatically detect `netlify.toml`:
   - **Publish directory**: `.` (Root)
   - **Build command**: *(None required)*
5. Click **"Deploy site"** — your store will be live with custom SSL and global CDN within seconds!

### Method 2: Netlify Drop (Instant Drag & Drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `HM-Sweets-web-app` folder directly into the upload area.
3. Your site is deployed immediately.
