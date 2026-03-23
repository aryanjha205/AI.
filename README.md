# Editor Pro AI 🎨✨

<p align="center">
  <img src="ai_app_icon.png" width="128" height="128" alt="Editor Pro AI Icon">
</p>

**Editor Pro AI** is a premium, AI-powered photo editing application designed for simplicity and power. Built with a sleek, modern interface, it transforms any image using cutting-edge AI processing directly from your browser.

---

## 🚀 Key Features

- **🪄 AI Magic**: Apply complex filters like Oil Painting, Cartoon, Vintage, and more with a single text command.
- **🎨 Premium Interface**: A beautiful, glassmorphism-based design that looks great on any device.
- **📲 PWA Support**: Install the app directly to your phone or PC via Chrome for an app-like experience.
- **🛠️ Manual Tweaks**: Fine-tune your images with brightness, contrast, and rotation controls.
- **🌗 Responsive Performance**: Fluid layout optimized for both desktop monitors and mobile screens.
- **🖼️ Comparison View**: Instantly see the difference between your original and the AI-processed version.
- **☁️ Cloud-Ready**: Save your processed masterpieces directly to the gallery.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS.
- **Aesthetics**: Glassmorphism UI, Phosphor Icons, Google Fonts (Outfit & Plus Jakarta Sans).
- **Backend API**: Integrated with a robust AI-processing backend via `fetch` API.
- **PWA**: Managed with a custom `manifest.json` and `sw.js` (Service Worker).

---

## 📦 Getting Started

### 🖥️ Local Usage
1.  Open [index.html](index.html) in any modern web browser (Chrome recommended).
2.  Ensure your backend is running at [ai-eight-tau.vercel.app](https://ai-eight-tau.vercel.app).
3.  Upload an image and start editing!

### 📲 Progressive Web App (PWA) Installation
- **On Mobile (Chrome/iOS)**: Open the URL and tap **"Add to Home Screen"** or use the **"Install"** button in the app navigation.
- **On Desktop (Chrome/Edge)**: Click the **Install** icon in the right side of the address bar.

---

## 🌐 Deployment

This project is pre-configured for **Vercel** deployment:
1.  Connect your repository to Vercel.
2.  Use the provided `vercel.json` for proper routing.
3.  Ensure the `API_BASE` in `index.html` matches your backend URL.

---

## 📁 Folder Structure

```text
/
├── index.html          # Main Application Entry
├── manifest.json       # PWA Configuration
├── sw.js               # Service Worker
├── ai_app_icon.png     # Premium App Icon
├── vercel.json         # Vercel Configuration
└── README.md           # Documentation
```

---

<p align="center">
  Developed with ❤️ for a seamless AI creative experience.
</p>