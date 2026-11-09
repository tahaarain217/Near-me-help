NEAR ME HELP — WEBSITE DEPLOYMENT

This is a static, single-file HTML prototype. It needs no npm, framework, database, or build command to display.

PUBLISH WITH GITHUB PAGES (FREE):
1. Sign in to https://github.com/ and create a new PUBLIC repository, for example: near-me-help.
2. Upload index.html (and optionally this README.txt) to the repository's main/root folder.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select Branch: main and Folder: /(root), then Save.
6. Wait for GitHub Pages to finish. Your public website URL will be:
   https://YOUR-GITHUB-USERNAME.github.io/near-me-help/
   Replace YOUR-GITHUB-USERNAME with your GitHub username.

IMPORTANT PROTOTYPE LIMITATIONS:
- The providers, locations, ratings, and sample bookings are demo data.
- Login/registration and app data are stored in the visitor's own browser localStorage.
- There is no shared server/database: different visitors do not see each other's accounts or bookings.
- Passwords are stored in browser localStorage in plain text. Do not use real passwords or personal data.
- Provider verification is only a demo toggle; it does not verify identity or certificates.
- Map positions/distances and some dashboard charts are simulated.
- Chat replies are simulated; there is no real-time messaging.
- No SMS/email alerts, online payments, live GPS, or backend authentication are implemented.

For a real public service, add a secure backend/database, password hashing, server-side role checks,
real provider verification, privacy/terms pages, and proper location/notification/payment integrations.
