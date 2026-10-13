# CYBERPULSE // Next-Gen 3D Cyber Store

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![License](https://img.shields.io/badge/license-MIT-cyan.svg)
![WebGL](https://img.shields.io/badge/WebGL-Three.js_r128-purple.svg)
![Hosting](https://img.shields.io/badge/Hosting-Vercel_Hobby_(₹0)-emerald.svg)

A modern, fully responsive, dark-theme 3D e-commerce storefront engineered with **HTML5**, **Tailwind CSS**, and **Three.js**. Features interactive mathematical 4D Torus Knot geometry, floating particle fields, glassmorphism aesthetics, in-memory cyber cart drawer, and a multi-protocol checkout modal.

---

## ⚡ Key Features

- **Hardware-Accelerated 3D Background**: Real-time Three.js WebGL canvas rendering a smooth parametric Torus Knot ($p=2, q=3$) and 1,200 particle stars.
- **Interactive 3D Controls**:
  - Live wireframe vs. solid mesh mode toggling.
  - Multi-hue spectrum switcher (Cyan, Purple, Emerald, Rose).
  - Hyper-drive speed boost on demand.
  - Mouse-position parallax response.
- **Dark Glassmorphism Architecture**: Multi-layer blurred glass panels (`backdrop-blur-xl`), neon gradient borders, and responsive grid layouts.
- **Interactive Cyber Cart**: Slide-out cart drawer with dynamic item counter badge, real-time subtotal calculation, and instant toast notifications.
- **Quantum Checkout**: Modal with protocol options (NeuralPay, USDT Crypto, Credit Card).
- **Zero Cost Deployment**: 100% free hosting under the **Vercel Hobby Plan (₹0)**.

---

## 🛠️ Tech Stack

- **Markup & Scripting**: Semantic HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN with custom theme extensions)
- **3D Graphics Engine**: Three.js (r128 WebGL via CDN)
- **Icons**: Lucide Icons CDN
- **Typography**: Google Fonts (*Space Grotesk* and *Outfit*)

---

## 🚀 Local Development

1. Clone or download the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cyberpulse-3d-store.git
   cd cyberpulse-3d-store
   ```

2. Start a lightweight local server:
   ```bash
   # Using Python:
   python3 -m http.server 8080

   # Or using Node.js:
   npx serve .
   ```

3. Open your browser at `http://localhost:8080`.

---

## 🌐 Deploy to Vercel (100% Free - ₹0)

### Method 1: Via GitHub & Vercel Dashboard (Recommended)

1. Push this folder to a new repository on GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Cyberpulse 3D Store"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/cyberpulse-3d-store.git
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
3. Click **Add New...** -> **Project**.
4. Select your `cyberpulse-3d-store` repository.
5. In **Build and Output Settings**, keep all defaults (Preset: *Other*, Root: `./`).
6. Click **Deploy**. Your site will be live on a `*.vercel.app` domain with free SSL in less than 30 seconds!

---

## 🔒 Security & Performance

- **Production Security Headers** configured in `vercel.json`:
  - `X-Content-Type-Options: nosniff`
  - `X-Frame-Options: DENY`
  - `X-XSS-Protection: 1; mode=block`
  - `Referrer-Policy: strict-origin-when-cross-origin`
  - `Permissions-Policy: camera=(), microphone=(), geolocation=()`
- **SEO & Social Cards**: Full OpenGraph and Twitter card integration with SVG favicon.
- **Image Optimization**: Lazy-loading and asynchronous decoding enabled for catalog assets.

---

## 📄 License

MIT License © 2026 CYBERPULSE INC.
