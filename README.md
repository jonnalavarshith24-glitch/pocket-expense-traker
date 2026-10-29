# PocketTrack — Expense Tracker

A responsive expense tracker built with React and Vite.

## Features
- Add, edit, and delete transactions
- Track income and expenses
- Search and filter by type/category
- Monthly overview and category breakdown
- Export transactions to CSV
- Saves data in the browser using localStorage (no backend required)

## Run locally
1. Install Node.js (LTS): https://nodejs.org/
2. Open a terminal in this folder.
3. Run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL printed in the terminal.

## Build check
```bash
npm run build
```

## Deploy
Push this repository to GitHub, then import it at https://vercel.com/new.
Vercel should detect Vite automatically. Use `npm run build` as the build command and `dist` as the output directory.
