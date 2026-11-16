# Momentum — Fitness Journey PWA

A lightweight installable fitness tracker designed for Android/Pixel phones.

## Included
- 24-week training plan with **Friday long runs**
- Daily session details and completion tracking
- Weekly schedule, strength, easy cardio, bike, optional jump rope and recovery
- Weight, waist, pull-up, longest-run and energy logs
- Weight trend chart, CSV export and JSON backup/restore
- Offline cache and local-device storage

## Install on Android
1. Host this folder on an HTTPS static host (for example GitHub Pages or Netlify).
2. Open the deployed URL in Chrome on your Pixel.
3. Use Chrome menu → **Install app** or **Add to Home screen**.
4. Open Momentum from the home screen. After the first successful load, core app files are cached for offline use.

A service worker generally requires HTTPS (localhost is also allowed for development). Opening `index.html` directly as a local file will not enable full PWA installation/offline caching.

## Data and privacy
All progress data is stored in this browser on this device. Clearing browser/site data may erase it. Use Settings → Download backup regularly. CSV export is available from Progress log.

## Training note
The 24-week plan is a template, not a medical prescription. Start conservatively, use conversational effort for easy and long runs, take recovery days, and reduce training if pain or unusual fatigue appears. Long-run distances are guides, not targets to force.
