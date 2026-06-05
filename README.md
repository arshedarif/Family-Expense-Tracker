# Family Monthly Expense

A minimal olive-green family expense tracker built as an iPad-friendly static website/PWA.

## What changed in this version

- Dashboard quick-action section buttons removed.
- Monthly expense tracking only.
- Dashboard and Summary number cards no longer show helper text below the numbers.
- Sidebar made more compact and narrower.
- Summary keeps professional color-coded cards for Total, Split per person, Ashif paid, Arshed paid, and Due.

## Features

- Monthly expense table: Date, Description, Ashif paid, Arshed paid, Total.
- Add/edit expense popup.
- Monthly dashboard.
- Professional summary and settlement calculation.
- Monthly comparison table.
- Category breakdown.
- Settings for names and currency label.
- JSON backup/import.
- CSV export for the selected month.
- iPad Add to Home Screen support when hosted over HTTPS.

## Calculation

The app assumes a 50/50 split.

- Total = Ashif paid + Arshed paid for the selected month.
- Split per person = Total / 2.
- If Ashif paid more than his split, Arshed owes Ashif the difference.
- If Arshed paid more than his split, Ashif owes Arshed the difference.

## Install on iPad

1. Upload this folder to any HTTPS static hosting.
2. Open the hosted `index.html` in Safari on iPad.
3. Tap Share.
4. Tap Add to Home Screen.
5. Open it from the Home Screen.

Data is stored in the browser on that device, so use Backup JSON regularly.
