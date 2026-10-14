# Daily Habit & Streak Tracker (PWA)

A free, installable, offline-capable habit and exercise tracker for Android browsers.

## Features
- Daily checklist with add/delete controls
- Completion ring, daily streaks, and a 7-day chart
- Local storage on this device/browser
- Automatic seven-day history rollover when the date changes
- Export/import JSON backup
- Service worker app-shell caching for offline use
- Install from Chrome as a standalone app

## Deploy on GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then press **Save**.
4. Wait for the Pages deployment to finish. Your URL should be https://ssccgl3377.github.io/habit-tracker/.

## Install on Android
1. Open the deployed URL in Chrome.
2. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
3. Confirm. Launch it from the new home-screen icon.

## Data and privacy
Habits are stored locally in the browser on your device. Clearing Chrome site data can erase them, so use **Export backup** periodically. Data does not automatically sync across devices.

## Notes
- Service workers and PWA installation require HTTPS (GitHub Pages provides HTTPS).
- The SVG icon is used as the manifest icon. Browser installation UI can vary by browser/version.
