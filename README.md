# DATAEX — Site Maintainer Guide

**What this is:** Static website for DATAEX (Windows) hosted on GitHub Pages at **https://www.dataexapp.com/**.  
All pages are plain HTML using Tailwind via CDN (no build step).

## Files
- `index.html` – landing (hero, features, FAQ, trial download)
- `pricing.html` – price **US$79.99**; “50% off first 100” text; Buy link (switch TEST→LIVE at launch)
- `refund.html` – refund policy
- `eula.html` – license agreement
- `privacy.html` – privacy policy
- `faq.html` (optional) – standalone FAQ if used in nav
- `sitemap.xml`, `robots.txt` – crawler files
- `assets/LOGO.png`, `assets/HERO.png` – images

## Edit guide (most common)
- **Price/promo:** `pricing.html`
- **Buy link:** `pricing.html` (change TEST to LIVE only when store is activated)
- **Trial download:** `index.html` (prefer the GitHub “releases/latest” link)
- **Header/Footer links:** update in each `.html` page if you add a new page

## Local preview
```bash
python -m http.server 8080
# open http://localhost:8080
