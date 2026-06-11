# 📝 ZenKeep — Decentralized Offline-First Notepad

ZenKeep is a lightweight, responsive, and completely **decentralized offline-first markdown notepad** that runs entirely serverless inside the browser. It enables you to write public notes or save private draft logs synced in real-time across all your devices using a peer-to-peer network.

Powered by **ZEN**—a zero-config decentralized peer-to-peer graph database.

## 🚀 Features

- 🌐 **100% Serverless**: No backend, no SQL, no configuration. Served strictly as static HTML, CSS, and JS.
- ⚡ **Real-Time P2P Sync**: Automatically updates and syncs modifications across peers in real-time.
- 🔐 **Cryptographic Auth**: Derives high-entropy cryptographic keypairs locally in-browser using Master Credentials (passwordless username + passphrase).
- 🎨 **Premium Aesthetic**: Curated light/dark theme modes, Outfit & IBM Plex Mono typography, responsive grids, and clean micro-animations.
- 📦 **Zero Dependencies**: Zero build tools, zero node packages. Loads everything instantly via CDN (Unpkg & Tabler Icons).

## 🛠️ Setup & Deployment

1. Clone or copy files to your static hosting directory.
2. Open `index.html`.
3. Locate `PUBLIC_VIEW_KEY` (around line 705) and paste your key inside the empty quotes if you want it to open a specific profile by default:
   ```javascript
   const PUBLIC_VIEW_KEY = 'YOUR_DERIVED_KEY_HERE';
   ```
4. Deploy the folder directly to GitHub Pages, Netlify, Vercel, or any other static web host.

## 📄 License
MIT License.
