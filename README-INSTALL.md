# 365 — One Year Project (Installable PWA)

## Publish on GitHub Pages
Upload the contents of this folder to the ROOT of the existing
`365-productivity-tracker` repository, keeping the `icons` folder.

The repository root should contain:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

Commit and push the changes. GitHub Pages will redeploy the site.

## Install on Android
1. Open https://zakariya772.github.io/365-productivity-tracker/ in Chrome.
2. Tap the Install app button on the page, or Chrome's ⋮ menu.
3. Choose Install app (or Add to Home screen) and confirm.

## Install on iPhone
1. Open the same URL in Safari.
2. Tap Share.
3. Choose Add to Home Screen, then Add.

## Offline use
Open the app online once so the service worker can cache the app shell.
The application shell can then load offline. Habit records are stored in
the browser's localStorage on that device; export a backup regularly.

## Updating later
When you publish a new release, change CACHE_NAME in sw.js, for example
from `365-productivity-v1` to `365-productivity-v2`, so installed copies
replace their old cached app shell.


## Outdoor movement GPS tracker
- Start an outdoor session and allow location access.
- GPS updates estimate distance using a great-circle distance calculation.
- Pause/resume and finish controls are provided; completed sessions are summarized in Insights.
- A spoken “Keep going and keep moving!” reminder plays every five active minutes when browser speech synthesis is supported.
- GPS requires HTTPS and location permission. Accuracy depends on the phone and GPS reception.
- Mobile browsers may suspend tracking when the app is backgrounded or the screen is locked. Keep the app open and screen awake for the most reliable results.
