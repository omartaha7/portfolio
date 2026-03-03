# Omar Taha — Portfolio Site

Automation & Development Portfolio — hosted on Render.com as a static site.

## Deployment Steps

1. Push this folder (`portfolio-site/`) to a **GitHub repository**
2. Go to [render.com](https://render.com) → **New** → **Static Site**
3. Connect your GitHub account and select the repository
4. Set these values:
   - **Name:** `omar-taha-portfolio` (or any name you like)
   - **Branch:** `main`
   - **Root Directory:** *(leave empty if repo root is this folder)*
   - **Build Command:** *(leave empty — no build needed)*
   - **Publish Directory:** `.`
5. Click **Create Static Site**
6. Render will give you a URL like `https://omar-taha-portfolio.onrender.com`

## Updating the site

After any edit to `index.html`:
```
git add .
git commit -m "update portfolio"
git push
```
Render auto-deploys on every push.

## Files

- `index.html` — the portfolio page (dark theme, collapsible sections, PDF-printable)
- `render.yaml` — Render configuration file
