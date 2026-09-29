# Hong Kong + Japan 2026 trip guide

A dependency-free mobile trip guide / PWA for 3–17 October 2026.

## Publish with GitHub Pages

1. Create a new GitHub repository, e.g. `japan-2026`.
2. Upload the **contents** of this folder to the repository root (`index.html`, `style.css`, `app.js`, `manifest.webmanifest`, `service-worker.js`).
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then Save.
7. GitHub will show the published URL. For a project repository it is normally `https://YOUR-USERNAME.github.io/japan-2026/`.

## iPhone / offline use

Open the published site in Safari while online, use **Share → Add to Home Screen**, and launch it once. The service worker caches the core guide for offline use. External Google Maps links still depend on connectivity / the Maps app.

## Updating

Edit the files on GitHub (or locally), commit to `main`, and GitHub Pages republishes. The service worker is network-first, so opening the site online picks up updated files and refreshes the cache.

## Privacy

This version intentionally excludes booking references, passport information, phone numbers and email addresses. GitHub Pages should be treated as public unless you are using an appropriate private publishing setup.
