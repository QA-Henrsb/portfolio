# Henrique Biver — QA Engineer Portfolio

Static one-page portfolio (no build step). `index.html` is fully self-contained
and links to `Henrique_Biver_Resume.pdf` in the same folder.

## Deploy to Vercel

### Option A — GitHub + Vercel (recommended)
1. Create a repo (e.g. `portfolio`) under github.com/qa-henrsb and push these files
   so `index.html` is at the repo root.
2. Go to vercel.com → **Add New… → Project → Import** your repo.
3. Framework Preset: **Other**. Leave Build Command empty and Output Directory empty.
4. Click **Deploy**. Your site goes live at `https://<project>.vercel.app`.

### Option B — Vercel CLI
1. Install: `npm i -g vercel`
2. From this folder: `vercel` (first run links/creates the project),
   then `vercel --prod` to publish.

Both keep `index.html` + the PDF together, so the "Download Resume" button works.
