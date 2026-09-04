# Security changes in v2

- JavaScript moved to a same-origin `app.js` file so the Content Security Policy can block inline script execution.
- Added a restrictive Content Security Policy.
- Added a `no-referrer` privacy policy.
- Pinch zoom / user scaling disabled at the user's request.
- Service worker cache bumped to `daily-stretch-v2` so installed copies refresh.
- The app still stores routine/streak data locally on the device and has no account, database, or backend.

GitHub Pages controls the HTTP response headers. This meta Content Security Policy provides useful browser protection, but a host that lets you configure security response headers can be hardened further.
