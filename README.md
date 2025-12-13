# SUPRA | OpenCorteX — Static Site

This repo hosts the SUPRA / OpenCorteX landing page as a **static HTML site**.

## What’s inside
- `index.html` — the website (single-file static page)

## How it’s deployed
This site is deployed with **Cloudflare Pages** directly from this GitHub repo.

### Cloudflare Pages settings
- Framework preset: **None**
- Build command: *(none)*
- Output directory: *(none / root)*

## Updating the site
1. Edit `index.html`
2. Commit + push to `main`
3. Cloudflare Pages automatically redeploys

## Local preview
Open `index.html` directly in your browser, or run a quick local server:

```bash
python3 -m http.server 8080
```

Then visit:
- `http://localhost:8080`
