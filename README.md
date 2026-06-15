# SMART-HUB

![PWA](https://img.shields.io/badge/PWA-Progressive%20Web%20App-purple?logo=googlechrome) ![HTML](https://img.shields.io/badge/Frontend-HTML%2FJS-orange?logo=html5) ![Status](https://img.shields.io/badge/Status-Active-brightgreen) ![Stars](https://img.shields.io/github/stars/hakunaTgl/SMART-HUB)

> **SMART-HUB** is a Progressive Web App (PWA) that provides a smart, installable web hub — accessible on any device, offline-capable, and fast-loading thanks to service worker caching.

---

## Features

- **Progressive Web App** — Installable on desktop and mobile from the browser
- **Offline Support** — Service worker (`sw.js`) enables offline functionality
- **Web App Manifest** — Full PWA manifest with icons and metadata
- **Fast Loading** — Cached assets for instant startup
- **Cross-Platform** — Works on all modern browsers and operating systems
- **No App Store Needed** — Install directly from the browser

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| App Shell | index.html |
| Service Worker | sw.js |
| PWA Config | manifest.json |
| Caching | Cache API |

---

## Project Structure

```
SMART-HUB/
├── index.html      # Main app shell
├── manifest.json   # PWA manifest (name, icons, theme)
└── sw.js           # Service worker for caching and offline support
```

---

## Quick Start

**Option 1 — Direct Browser:**
```
Open index.html in any modern browser
```

**Option 2 — Local Server:**
```bash
git clone https://github.com/hakunaTgl/SMART-HUB.git
cd SMART-HUB
npx serve .
# Open http://localhost:3000
```

**Option 3 — Deploy to Netlify:**
```
Drag the folder to https://drop.netlify.app
```

---

## PWA Installation

1. Open the app in Chrome, Edge, or Safari
2. Look for the **Install** prompt in the address bar
3. Click **Install** to add to your home screen or desktop
4. Launch like a native app!

---

## Roadmap

- [x] Core PWA structure
- [x] Service worker implementation
- [x] Web app manifest
- [ ] Push notifications
- [ ] Background sync
- [ ] Full hub dashboard UI
- [ ] API integrations

---

*Built by [@hakunaTgl](https://github.com/hakunaTgl)*
