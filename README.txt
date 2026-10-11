SENSEI ATTENDANCE — iPad-friendly PWA prototype

FILES
- index.html: the attendance app
- manifest.webmanifest and icons/: Home Screen app metadata and icon
- sw.js: offline app-shell cache

IMPORTANT
This prototype stores attendance records in the browser's local storage on the device.
It does not automatically sync between iPad and MacBook. Export a backup regularly in
Tetapan & Sandaran. The app shell can work offline after it has been installed/loaded
once, but hosting it on an HTTPS website is required for Safari's Add to Home Screen
and service-worker offline support. Opening index.html directly from Files is not the
same as installing a PWA.

INSTALL ON IPAD
1. Upload the contents of this folder to an HTTPS static host.
2. Open the hosted URL in Safari on the iPad.
3. Tap Share > Add to Home Screen > Add.
4. Open the Sensei Attendance icon from the Home Screen.
5. Test with dummy data first and export a backup.

DESIGN
Soft Sage Academic: sage green, cream, muted mustard accents, rounded cards and a simple
clipboard/check icon.
