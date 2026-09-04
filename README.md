# Daily Stretch PWA

- `index.html` — app UI and logic
- `manifest.json` — installable PWA metadata
- `sw.js` — offline caching and notification display support
- `icons/` — app icons

The app stores stretches, streak, XP, and reminder preference locally on each device.

Important: iPhone Home Screen web apps can receive Web Push notifications, but reliable scheduled reminders while the app is closed require a web-push backend/service. This starter includes notification permission + a test notification, not a remote push server.
