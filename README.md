My Expense Tracker (free iPhone web app)

Included features

• Income and expense entry in PKR
• Expense categories and payment methods
• Monthly income/expense overview and spending-by-category chart
• Monthly category budgets with over-budget indicators
• Delete transactions
• CSV backup export and CSV transaction import
• Local browser storage and basic offline caching after first load

Important limitations

• Records stay in the browser storage on one device/browser; they do not sync to iCloud or other devices.
• Export CSV backups regularly. Clearing Safari website data, deleting browser data, or changing browsers can remove or hide records.
• GitHub Pages repositories used for free hosting are generally public when using GitHub Free. Do not put personal transaction data in the repository. The site code is separate from records stored locally in the browser.
• This is a personal-use starter project, not audited financial software. Check calculations and keep backups.

Publish using GitHub Pages (free)

1. Sign in to GitHub and create a new repository, e.g. my-expense-tracker.
2. For GitHub Free Pages, use a public repository. Keep only these app files in it; do not upload your CSV backups.
3. Upload index.html, manifest.json, and sw.js to the repository root.
4. Open repository Settings → Pages.
5. Under build/deployment, choose Deploy from a branch, select main and / (root), then Save.
6. Wait for the published URL shown in Pages settings. It will look like https://YOUR-USERNAME.github.io/my-expense-tracker/.
7. Open that URL in Safari on your iPhone.
8. Tap Share → Add to Home Screen. If offered, turn on Open as Web App, then tap Add.
9. Open the new Home Screen icon, add a small test transaction, close/reopen the app, and confirm the record remains.
10. Export a CSV backup after adding real records.

Updating the app

Edit the relevant files in the repository and commit the changes. If the app still shows an older version, close it and reopen; you may need to refresh or clear the site’s cached app files. Do not clear website data until you have exported your transaction backup.