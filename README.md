# Travel Reimbursement Log

A simple offline-capable PWA for logging business travel and tracking mileage reimbursement.

## Deploy on GitHub Pages

1. Create a new GitHub repo (e.g. `travel-log`).
2. Upload these files to the **root** of the repo: `index.html`, `manifest.json`, `icon.svg`, `service-worker.js`.
3. Go to **Settings → Pages**, set Source to the `main` branch, root folder.
4. Your app will be live at `https://<your-username>.github.io/travel-log/`.
5. Open the link on your phone and choose **Add to Home Screen** — it will launch full-screen like a native app, and works offline after the first load.

## Notes

- All your data (trips, rate, reimbursement status) is stored locally in the browser on your device — nothing is sent to a server.
- Use **Backup (JSON)** regularly and keep the file somewhere safe (e.g. Google Drive) in case you switch phones or clear browser data.
- **Restore Backup** loads a previously saved JSON file back into the app.
