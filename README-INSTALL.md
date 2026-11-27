# 365 — One Year Project

## Deploy the polished version
Upload the contents of this folder to the ROOT of your existing GitHub Pages repository. Keep the `icons` folder.

Files: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/icon-192.png`, `icons/icon-512.png`.

Commit and push the changes. The service worker cache is versioned `365-productivity-v3` to refresh installed copies.

## Install on Android
Open your GitHub Pages URL in Chrome and choose Install app from the page or Chrome menu.

## Install on iPhone
Open the URL in Safari, tap Share, then Add to Home Screen.

## Features retained
Daily habit tracking, 365-day heatmap, focus timer with completion beep, GPS exercise distance and duration tracking, five-minute spoken encouragement, reflections, insights, and local backup.

GPS needs HTTPS and location permission. Mobile browsers can suspend GPS and timers while backgrounded or when the screen is locked, so keep the app open for the most reliable tracking. Data is stored locally in the browser; export backups regularly.


## MoveMate voice coach
MoveMate welcomes the user when an outdoor session starts, gives rotating encouragement every five active minutes, celebrates each whole kilometre, and congratulates the user when the session is finished. Voice can be turned off in the exercise panel; the preference is saved on the device. The browser's built-in speech synthesis is used, so available voices depend on the device and browser.
