# Samara Care ERP

GitHub Pages compatible Assisted Living Management System.

## Production URL

`https://rajaiahboomi-crypto.github.io/Samara-Care-ERP-v1.0/`

## Architecture

- GitHub Pages: frontend/PWA
- Supabase Auth: employee login
- Supabase PostgreSQL: shared operational records
- Supabase Storage: patient photographs and documents
- Supabase Realtime: live synchronisation
- Supabase Edge Functions: optional WhatsApp/SMS provider integration

## Repository structure

- `index.html`, `app.js`, `styles.css`: application
- `config.js`: public Supabase project configuration
- `manifest.webmanifest`, `service-worker.js`, `icons/`: PWA
- `supabase/`: database upgrade scripts and optional server functions
- `.github/workflows/pages.yml`: automatic GitHub Pages deployment
- `docs/`: setup and release instructions

## Deployment

Upload the contents of this repository to the root of `Samara-Care-ERP-v1.0`, commit to `main`, and enable GitHub Pages using **GitHub Actions** as the source.

The Supabase publishable key in `config.js` is a public browser key. Never place a secret/service-role key in GitHub.
