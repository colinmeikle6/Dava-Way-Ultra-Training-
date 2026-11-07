DAVA WAY ULTRA COACH — INSTALLABLE WEB APP PACKAGE

CONTENTS
- index.html: training dashboard
- manifest.webmanifest: app name, icon and install/display settings
- sw.js: offline app-shell caching
- icons/: 192px and 512px app icons
- Dava_Way_Ultra_Training_Plan.xlsx: detailed 40-week programme

IMPORTANT
A Progressive Web App must be served from HTTPS (or localhost) to be installable and to use offline caching. Opening index.html directly from a phone's Downloads folder will not install it as an app.

EASIEST FREE HOSTING ROUTE: GITHUB PAGES
1. Sign in to GitHub or create an account at https://github.com.
2. Create a new public repository named dava-ultra (or another name you prefer).
3. Upload all files and folders in this package to the repository root. Do not upload the ZIP itself; extract it first.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish. Your site URL will be shown on the Pages settings screen, normally https://YOUR-USERNAME.github.io/dava-ultra/.
7. Open that HTTPS URL in Chrome on Android. Use the browser menu > Install app (or Add to Home screen). If an Install app button appears in the dashboard, you can use that too.

ANDROID
After installation, launch Dava Ultra from the home-screen icon. Open it online once before going offline so the app shell is cached. Training data is stored in this browser's local storage on this device. Export/backup your Garmin CSV separately; clearing browser site data can erase local training records.

GARMIN
This package supports Garmin Connect CSV import, not direct live Garmin account authorisation/synchronisation.

DATA / CONFIDENCE
The confidence indicator is a simple training-trend score based on imported mileage, long-run completion, consistency and manually logged weekly RPE. It is not a validated probability of finishing under five hours.
