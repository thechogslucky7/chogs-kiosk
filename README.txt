# Chogs Kiosk V4 — iPhone Ready

This package keeps the existing Chogs Kiosk V4 app and adds:
- PWA manifest
- iPhone/iPad home-screen app configuration
- Service worker for app-shell/offline loading
- Chogs Kiosk app icons

## Important
The app stores transactions in the browser's local storage, as in the original V4 design. The PWA package does NOT add cloud synchronization or move your business records to a server.

## Install on iPhone
For the full "Add to Home Screen" / standalone-app experience, the package should be hosted from an HTTPS website.

1. Upload this folder to a static HTTPS host.
2. Open the site in Safari on your iPhone.
3. Tap Share.
4. Choose "Add to Home Screen".
5. Open Chogs Kiosk from the Home Screen.

If you open `index.html` directly from the Files app, the existing app can still run as a web page, but iOS PWA installation behavior is more limited.

## Backup
Use Chogs Kiosk's built-in Export Backup regularly. The backup remains a local JSON file unless you choose to store it elsewhere.
