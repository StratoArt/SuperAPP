# Demoplot Dashboard — GitHub + Google Apps Script

Data source yang dipakai berasal dari file terbaru user: **DEMO DR All IVAN H1 + Q3-2 - DEMOPLOT.csv**.

Data saat ini:
- Total rows: 40
- Q3 rows (Month Plan 7/8/9): 10
- Q3 status: {'Planned': 8, 'On Progress': 2}

## 1. Google Sheets
Upload CSV terbaru ke Google Sheets dan pastikan sheet database bernama `DEMOPLOT`.
Jika ingin fungsi foto nanti, buat sheet `PHOTO`.

## 2. Apps Script
Buka Extensions > Apps Script dari spreadsheet.
Replace Code.gs dengan `Code.gs` dari paket ini.
Deploy > New deployment > Web app:
- Execute as: Me
- Who has access: sesuai kebutuhan
Copy URL `/exec`.

## 3. GitHub Pages
Upload `index.html` ke repository GitHub.
Di `index.html`, ganti:
`const API="PASTE_APPS_SCRIPT_WEB_APP_URL_HERE";`
menjadi URL Apps Script `/exec`.

Settings > Pages > Deploy from branch > main / root.

Frontend = GitHub Pages.
Backend/API = Apps Script.
Database = Google Sheets.

Tahap berikutnya: detail drawer, Add/Edit, upload foto ke Drive, dan tombol Lead My Bayer.
