# Helm — iOS PWA Installation Guide

## How to install on iPhone / iPad

1. **Host on GitHub Pages** (free, 2 minutes):
   - Go to github.com → New Repository → name it `helm-app` → Public
   - Upload ALL files in this folder (index.html, manifest.json, service-worker.js, icons/)
   - Go to Settings → Pages → Source: "main" branch → Save
   - Your URL will be: `https://YOUR-USERNAME.github.io/helm-app/`

2. **Open on iPhone**:
   - Open **Safari** (must be Safari, not Chrome)
   - Go to your GitHub Pages URL
   - Wait for it to fully load

3. **Add to Home Screen**:
   - Tap the **Share button** (box with arrow at bottom)
   - Scroll down and tap **"Add to Home Screen"**
   - Name it **"Helm"** → tap **Add**

4. **Done!**
   - Helm icon appears on your home screen
   - Opens full-screen like a native app
   - Works completely **offline** after first load
   - All data saved on-device (localStorage)

## What you get on iOS
- ✅ Full-screen app (no browser bar)
- ✅ Helm icon on home screen
- ✅ Works offline
- ✅ All features identical to Android version
- ✅ Splash screen on launch

## Notes
- Data is stored separately on each device
- To sync: use the Export Summary feature and share manually
- Updates: when you update index.html on GitHub, it auto-updates on device next time user is online

## Files in this package
```
index.html          — The complete Helm app
manifest.json       — PWA config (name, colors, icons)
service-worker.js   — Offline caching
icons/              — App icons (all iOS + Android sizes)
```
