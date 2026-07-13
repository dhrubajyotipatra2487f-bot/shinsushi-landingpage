# Sushi Bar 心 -SHIN- — Official Landing Page

Cinematic one-page site for **Sushi Bar 心 -SHIN-**, Japanese sushi & izakaya on Angkor Night Market Street, Siem Reap, Cambodia.

**Live site:** https://dhrubajyotipatra2487f-bot.github.io/shinsushi-landingpage/

## Stack
- Single static `index.html` — zero build step, zero external JS (GSAP + ScrollTrigger inlined)
- Scroll-driven cinematography, EN / 日本語 language switch, JSON-LD Restaurant schema
- Optimized WebP assets (whole site ≈ 1.4 MB, initial view ≈ 500 KB)

## Editing
Everything lives in `index.html` (styles + scripts inline). Images live in `assets/`.
Japanese translations: search for `var dict` in `index.html`.

## Hosting
Served with GitHub Pages from the `main` branch (root). Custom domain can be added later
in **Settings → Pages** — then update `<link rel="canonical">` and `og:url` in `index.html`.

## Credits
Photos © Sushi Bar Shin & guests (used with the owner's permission).
