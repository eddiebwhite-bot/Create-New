# River Bridge Route Optimizer (Single-file v9a)

This is a single, self-contained HTML that you can open in any modern browser or drop into Netlify's drag‑and‑drop.

## What's inside
- Route optimization (fastest or shortest) using Google Distance Matrix
- Map + Directions link
- Delivered checkbox per stop with time stamp
- Signature capture for customer + driver (touch friendly)
- Photo proof per stop (compressed in-browser)
- Print Preview → Invoice or Receipt (includes photos + status)
- CSV Export with iOS/Safari-safe download

## Setup
1) Open `River-Bridge-Route-Optimizer-v9a.html` in your browser.
2) In step **1) Connect Google**, paste your **Google Maps JavaScript API key**.
   Enable these in Google Cloud: **Maps JavaScript API**, **Distance Matrix API**, **Directions API**.
3) Enter addresses and click **Optimize Route**.
4) Use **Open in Google Maps** for turn-by-turn navigation.

## Deploy to Netlify (free *.netlify.app)
- Go to https://app.netlify.com/drop
- Drag just this `index.html` (rename the file to `index.html` first) into the page.
- Netlify will deploy and give you a `https://<site>.netlify.app` link.
- No domain configuration needed.

## Notes
- Max 25 total points (origin + waypoints + destination) per Google Directions.
- All data stays on-device. No server is used.
- For Google Drive saving and URL handoff features, use the multi-file "v9 Drive" build from our canvas instead.