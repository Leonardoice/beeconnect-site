# Foundwick — homepage (foundwick.com)

Static site for the Foundwick homepage (formerly beeconnectagency.com). Auto-deploys to Cloudflare Pages on push to `main`.

## Files
- `index.html` — the homepage
- `llms.txt` — AI-crawler readable summary (AIO/GEO)
- `robots.txt` — explicitly allows AI crawlers
- `sitemap.xml`
- `bookkit/` — BookKit live demo (served at foundwick.com/bookkit/demo.html)
- `repkit/` — RepKit live demo (served at foundwick.com/repkit/demo.html)

## Deploy
Connected to Cloudflare Pages (project: beeconnect-site — name kept from pre-rebrand). Push to `main` -> auto-build (no build step) -> live at foundwick.com.

## Notes
- 2026-06-21: Rebuilt the "Proof" section to show our own product demos (BookKit, RepKit) instead of client references. Standing rule: no client names or results appear on this site without written permission and a completed job.
- 2026-07-13: Replaced the labeled sample-testimonial card with the live-demo proof card. Same standing rule applies to all future proof content.
- 2026-06-22: Rebranded to Foundwick. beeconnectagency.com 301-redirects here.
- 2026-06-26: Moved BookKit/RepKit demos into this repo (`/bookkit/`, `/repkit/`). Previously they lived on `demos.beeconnectagency.com`, but the rebrand redirect caught that subdomain and the demo links were dead. Now they're served from foundwick.com directly.
