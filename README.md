# MARKA Boucle Listing — Vercel deploy

Single-file static site. Everything (CSS, JS, images, fonts) is inlined into `index.html`.

## Deploy

### Option 1 — Vercel CLI
```bash
cd deploy
npx vercel
# or for production:
npx vercel --prod
```

### Option 2 — Drag & drop
1. Go to https://vercel.com/new
2. Drag the `deploy` folder into the upload area
3. Click **Deploy**

### Option 3 — Git
1. Push the `deploy` folder contents to a GitHub repo
2. Import the repo on Vercel — no build config needed

## Files
- `index.html` — the full page (self-contained, ~1.8MB)
- `vercel.json` — minimal config (clean URLs)
