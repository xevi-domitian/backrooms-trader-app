# Backrooms Survival Shop Manager

A small local app for managing the shop catalog, stash, sales, and loss reports.

## Run on Windows

1. Extract the entire app folder if it came in a ZIP file.
2. Open the `installers` folder and run `node-v26.13.1-x64.msi`.
3. Follow the installer prompts. Node.js only needs to be installed once on this computer.
4. Return to the app folder and double-click `start-shop-manager.bat`.
5. The app opens at <http://127.0.0.1:3000/>.

Keep the server's command window open while using the app. Close that window when you are finished.

Opening `index.html` directly will load the page styling, but browsers do not allow it to read or save the app's JSON data. Use the launcher for the full app.

## Data and sharing

The app stores its data as JSON files in the `data` folder. Use **Settings** in the app to export or import backups, or make a copy of the `data` folder while the app is closed.

The app runs locally and has no sign-in or access control. Sharing a copy of this folder gives someone a copy of the data; it does not sync changes between devices. Do not expose the app server to the public internet.

## Stuff

Made for the the traders and sellers of the backrooms community. xoxo Luka

P.S: If you have ideas on what to do to improve this please DM me on discord via @is.mxm

