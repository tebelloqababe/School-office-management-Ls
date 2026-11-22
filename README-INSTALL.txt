TARKY SCHOOL OFFICE MANAGEMENT SYSTEM
Installable offline web-app package

CONTENTS
- index.html: the TARKY application
- manifest.webmanifest: install information and app icon references
- service-worker.js: caches the app for offline opening
- icons/: Android and Windows app icons

IMPORTANT
This package is prepared for PWA installation, but a PWA must be opened from a secure HTTPS website (or localhost) to install and register its offline service worker. Opening index.html directly from a file manager is not enough for home-screen installation.

NEXT STEPS
1. Publish these files together to a free HTTPS static host, keeping the folder structure.
2. Open the HTTPS address on Android Chrome, load it once while online, then use the browser menu > Install app or Add to Home screen.
3. On Windows, open the same HTTPS address in Microsoft Edge, then use the menu > Apps > Install this site as an app.
4. After installation and the first successful load, open TARKY while offline to test it.
5. Keep using Backup & Restore to move data between devices. Data is stored separately in each device/browser; there is no automatic sync.

DATA AND SECURITY NOTES
- The app uses browser local storage. It is not encrypted and is not a secure multi-device database.
- Do not share administrator passwords. Keep regular JSON backups on a USB drive.
- Installing the app does not copy or merge records from one device to another.
