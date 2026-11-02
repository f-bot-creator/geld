# Geld

Static, offline-capable personal budget web app. It runs entirely in the browser and is installed on an iPhone Home Screen from GitHub Pages.

**Live site:** https://f-bot-creator.github.io/geld/

## Install on iPhone

1. Open the live site in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.

## Updates

The service worker caches the app shell. Bump `CACHE_VERSION` in `sw.js` on every update so installed copies pick up the new files.
