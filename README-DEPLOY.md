# PROJECT RAINDROP — Android PWA package

This folder is the installable web-app package for Project Raindrop.

## Deploy
Upload the contents of this folder to any HTTPS static host (GitHub Pages, Cloudflare Pages, Netlify, etc.).

Important:
- The app must be served over HTTPS for service-worker/PWA behavior.
- Keep `index.html`, `manifest.webmanifest`, `sw.js`, and `icons/` together.
- Live weather/model API calls are deliberately NOT cached by the service worker.

## Install on Android
1. Open the deployed HTTPS URL in Chrome on the phone.
2. Use Chrome's menu and choose **Install app** (wording may vary).
3. Launch **Raindrop** from the Android home screen.

Future Raindrop releases can be deployed to the same URL; the installed app will receive the updated web assets.
