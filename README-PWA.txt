MY ADMISSION — STUDY TRACKER PWA

Files:
- tracker.html: the existing Study Tracker with PWA metadata and service-worker registration
- manifest.json: install/app display information
- service-worker.js: offline app-shell caching
- icons/: app icons for Android and iPhone

IMPORTANT:
1. Upload these files to the ROOT of your existing GitHub repository, keeping the icons folder.
2. This package uses tracker.html as the app page. Keep the filename tracker.html.
3. Do not delete your other existing files unless you want to.
4. Open the published tracker.html URL while online and wait a few seconds before testing offline.
5. On Android, use Chrome menu > Install app (or Add to Home screen).
6. On iPhone, open in Safari > Share > Add to Home Screen.
7. Progress and theme are stored locally in the browser on that device. There is no cloud sync.
8. When updating the app later, the service worker cache version may need to be incremented.

This PWA has no ad code. iOS/Android installation prompts and menus can vary by browser/OS version.
