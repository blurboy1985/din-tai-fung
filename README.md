# Din Tai Fung Singapore Queue Links

A single-page directory of all 30 Din Tai Fung Singapore outlets, with a direct
queue link for each outlet.

- **Site:** https://dtf.danielquek.com (Cloudflare Pages, deployed from this repo's `master` branch)
- **Page:** `index.html` — search by outlet or area, filter by region, and tap
  "Join the queue" to open that outlet's queue page, or copy the queue link.

## What the links are

Each "Join the queue" button opens that outlet's own inline.app queue page —
the same queue system opened by the outlet's in-store QR code. The links were
captured on 1 November 2026 and have not been live-tested end to end, so a link
may have changed since then; if one does not work, check with the outlet
directly.

Din Tai Fung Singapore is walk-in only — these are queue links, not advance
reservations.

## Outlets

All 30 outlets are listed on the site with their address and phone number:
Paragon, BreadTalk IHQ, Chinatown Point, City Square Mall, Compass One,
Geneo Science Park, Great World, IMM, JEM, Jewel Changi Airport, Junction 8,
Jurong Point, Marina Bay Link Mall, Marina Bay Sands, NEX, One Holland Village,
Northpoint City, Parkway Parade, Plaza Singapura, Punggol Coast Mall,
Raffles City, Resorts World Sentosa, Suntec City, Tampines Mall,
The Centrepoint, The Seletar Mall, Velocity @ Novena Square, VivoCity,
Waterway Point, and Wisma Atria.

## Deploying

This is a static site with no build step. Cloudflare Pages serves `index.html`
from the `master` branch. To update the site, edit `index.html` (or regenerate
it) and push to `master`; Cloudflare Pages redeploys automatically.

## Disclaimer

Unofficial shortcut list. Not affiliated with, endorsed by, or connected to
Din Tai Fung or inline.app.
