PA-30 Systems PWA

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/

To put this on an iPad Home Screen:
1. Host this folder on any HTTPS static website (Netlify Drop, GitHub Pages, Vercel, etc.).
2. Open the HTTPS site in Safari on the iPad.
3. Tap Share -> Add to Home Screen -> Add.
4. After the first successful load, the service worker caches the app for offline use.

Important: iPadOS does not reliably install a local .html file from Files/ChatGPT as a Home Screen PWA. It needs to be opened from an HTTPS website.
