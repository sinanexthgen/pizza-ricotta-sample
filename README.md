# Pizza Ricotta — Landing Page

The official business website for **Pizza Ricotta**, Kozhikode (India), built to
serve as the verified website for Meta / WhatsApp Business (WATI) setup.

Pure HTML + CSS, no build step. Uses the brand's yellow / green / cream palette,
campaign-style bold typography, and the official logo.

## Files
- `index.html` — the page
- `styles.css` — all styling
- `assets/logo.jpg` — brand logo (also used as favicon)
- `vercel.json` — clean-URL config
- `package.json` — local dev server script

## Run locally

```bash
npm install     # first time only — installs the local dev server
npm run dev     # serves at http://localhost:3000
```

## Deploy (GitHub → Vercel)

1. Push this folder to a GitHub repository.
2. On Vercel: **Add New → Project → Import** the repo.
3. Framework preset: **Other** (no build needed). Leave Build Command empty and
   Output Directory as the repo root.
4. Deploy — Vercel gives you a `*.vercel.app` link to share with the team.

No framework or build command is required; Vercel serves the static files directly.
