# Muscle Factory — Android installable web app

Your original HTML design is retained. The PWA manifest, app icons, and service worker have been added.

## Publish it (free) with GitHub Pages
1. Sign in to https://github.com and create a new **public** repository (for example `muscle-factory`).
2. Upload **all five files** from this folder to the repository root: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish. Open the published `https://YOUR-USERNAME.github.io/muscle-factory/` address in Chrome on Android.
6. Tap Chrome **⋮ → Install app** (or **Add to Home screen**) and confirm.

## Notes
- Installability requires a secure HTTPS website; opening the HTML directly from the phone's Files app is not enough.
- The app's workout data is stored in the browser's local storage. Keep using the same installed app/browser profile, and use its Export JSON feature for backups.
- The service worker caches the app shell for offline launch after the first successful visit. External Google Fonts may still require internet.
