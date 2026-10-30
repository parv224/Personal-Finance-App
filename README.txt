POCKET FINANCE — MOBILE-READY OFFLINE PWA (V2)

This is a private, local-first Progressive Web App. It has no paid services, ads, bank connection, login, analytics, or external API.

FEATURES
- Income, expense and investment tracking
- Savings goals
- EMI / loan list with upcoming 3-month due calendar and Mark Paid action
- Monthly total budget and category budgets
- Recurring transaction templates (not posted automatically)
- Monthly, yearly and category reports with a six-month cashflow chart
- Separate actual bank/wallet balance entry compared with tracked net cash
- JSON export/import backup
- IndexedDB storage and offline service-worker cache
- Mobile-first responsive layout and installable PWA manifest

INSTALL ON ANDROID
1. Extract this ZIP.
2. Create a free GitHub repository and upload the CONTENTS of this folder (index.html, app.js, style.css, sw.js, manifest.webmanifest, icon.svg, README.txt).
3. GitHub repository > Settings > Pages > Deploy from branch > main > /(root) > Save.
4. Wait for deployment, open the GitHub Pages HTTPS URL in Chrome on your phone.
5. Open once while online. Chrome menu (⋮) > Install app or Add to Home screen.
6. Launch from the new home-screen icon. After first load, the app shell works offline.

INSTALL ON IPHONE
1. Deploy to HTTPS using the same steps.
2. Open the URL in Safari, tap Share > Add to Home Screen.

DATA / PRIVACY
- Transaction data is stored in IndexedDB in that browser on that phone.
- Budget limits and actual balance are stored locally in browser storage.
- No cloud sync: the phone is the source of truth.
- Export a JSON backup regularly. Importing replaces existing transaction records.
- Clearing browser/site data may erase app data.
- If you mark an EMI paid, an expense is created in the selected due month. Review date and category.
- Recurring rules are templates only; add transactions yourself when they occur.
- Tracked net cash is income minus expenses and investment contributions; it is not a bank feed. Enter your actual bank balance separately.

DISCLAIMER
This is a personal record-keeping tool, not accounting, tax, investment, or banking software. Verify entries and backups.
