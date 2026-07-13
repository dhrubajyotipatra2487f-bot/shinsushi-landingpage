# Sushi Bar 心 -SHIN- — Official Landing Page

Cinematic one-page site for **Sushi Bar 心 -SHIN-**, Japanese sushi & izakaya on Angkor Night Market Street, Siem Reap, Cambodia.

**Live site:** https://dhrubajyotipatra2487f-bot.github.io/shinsushi-landingpage/

## Stack
- Single static `index.html` — zero build step, zero external JS (GSAP + ScrollTrigger inlined)
- Scroll-driven cinematography, EN / 日本語 language switch, JSON-LD Restaurant schema
- Optimized WebP images (whole site ≈ 1.4 MB)

## Images
Images are currently served from stable public URLs (pub.hyperagent.com).
**Optional hardening:** upload the `assets/` folder (provided as assets.zip) to this repo,
then replace `https://pub.hyperagent.com/api/published/<id>/<file>` with `assets/<file>`
in `index.html` (search & replace — every filename matches 1:1).

## Editing
Everything lives in `index.html` (styles + scripts inline).
Japanese translations: search for `var dict`.

## Hosting
GitHub Pages. Custom domain later: **Settings → Pages → Custom domain**,
then update `<link rel="canonical">` and `og:url` in `index.html`.

## Credits
Photos © Sushi Bar Shin & guests (used with the owner's permission).
