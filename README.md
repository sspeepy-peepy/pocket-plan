# Pocket Plan

A small, phone-friendly spending plan and daily expense tracker. It runs as a static website and can be published free with GitHub Pages.

## What it does

- Lets you set take-home income, a savings target, bills and essentials, and a monthly flexible-spending limit.
- Tracks short-term and long-term savings goals, including recurring targets such as saving $3,000 every six months, with progress, suggested monthly contributions, and editable contribution history.
- Keeps income and monthly plan settings editable separately for each month.
- Lets you plan with an estimated monthly take-home amount, then log actual paychecks by date without counting the estimate as received money.
- Adds weekly limits for eating out, going out, and small purchases, with the remaining amount calculated from this week's logged expenses (Monday to Sunday).
- Tracks dated purchases by category, with edit and delete controls.
- Includes a separate tab for monthly recurring payments, with due days; active payments count toward monthly spending and the category chart.
- Shows how much of the flexible limit remains, a six-month income/spending/savings-goal comparison, and a category doughnut chart.
- Starts in dark mode and includes a light/dark toggle.
- Remembers information in the current browser and supports JSON backup/restore, CSV export, and a monthly backup reminder.
- Includes a basic offline cache and can be added to an iPhone home screen from Safari.

## Publish with GitHub Pages

1. Create a new **public** repository on GitHub.
2. Upload `index.html`, `manifest.json`, `icon.svg`, and `sw.js` to the repository's top level. Keep the file names as shown.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait for GitHub Pages to provide the site URL. Open that URL on your iPhone in Safari.
5. In Safari, tap **Share → Add to Home Screen**.

GitHub Pages may take a few minutes to publish the first time. Use the Pages URL (HTTPS) on iPhone so the offline cache and home-screen installation work.

## Important data note

The app stores data in browser storage on the device where you enter it. It does **not** sync across devices or send information to GitHub. Download a backup periodically from Settings & backup. Clearing Safari website data can remove the locally stored plan, so restore your backup if that happens.

## Customize

The app is intentionally a static site with no build step or external dependencies. Edit `index.html` to change categories, labels, or appearance, then commit and push the changes to update the Pages site.
