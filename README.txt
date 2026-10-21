TRAILER SAFETY INSPECTION — free PWA for Android and iPhone

FILES: index.html, manifest.webmanifest, sw.js, icon.svg

QUICK TEST: Open index.html in a browser (storage/camera behavior may vary on file://).
RECOMMENDED INSTALL: Host all four files together on an HTTPS static host such as GitHub Pages. Open its HTTPS URL in Chrome (Android) or Safari (iPhone). Use Add to Home Screen / Install App. Load once while online to cache app files for offline use.

LOCAL DATA: Each device stores its own records and compressed photos in IndexedDB. No cloud upload or shared database. If the browser/app data is cleared, records are lost. Private browsing and device storage policies may delete them earlier. Data will be purged when app opens, resumes or remains running (hourly); iOS/Android do not guarantee a web app can run cleanup while fully closed. Expiration is 30*24 hours after record creation.

CHECKLIST: This is a generic visual inspection template, not legal proof of insurance or regulatory compliance. Adapt criteria to site-specific policies and consult safety/compliance management before production use. A passing checklist does not override management approval.

LIMITATIONS: File inputs may allow existing gallery photos depending on platform. To strictly enforce live camera capture and guarantee background deletion while closed, build a native app. If the organization requires evidence retention, 30 days may be too short.
