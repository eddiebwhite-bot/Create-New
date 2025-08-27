# River Bridge Route Optimizer — Single File (v9)

This is a **drag‑and‑drop** build: just open `index.html` or drop the folder on **Netlify Drop** to get a public link.

## Quick Start
1. Open `index.html` on your laptop/phone.
2. Paste your **Google Maps API key** and click **Load Google Maps**.
   - Enable these APIs in Google Cloud: **Maps JavaScript API**, **Distance Matrix API**, **Directions API**.
3. Enter **Start**, **Stops** (one per line), and **End** (optional). Toggle round‑trip if needed.
4. Click **Optimize Route**.
5. Tap **Open in Google Maps** for navigation, **Export Manifest (CSV)**, or **Generate Invoice / Receipt** for a print/PDF.
6. Capture **customer/driver signatures** and **photo proof** right in the app.

## Driver Mode + PIN
- Add `?driver=1` to the URL (or use the header toggle) to hide pricing.
- Optional **Owner PIN** locks exiting Driver Mode.

## Deploy to Netlify (free netlify.app URL)
- Go to **https://app.netlify.com/drop**.
- Drag the **unzipped folder** (or the ZIP) that contains `index.html`.
- You’ll get a `*.netlify.app` URL automatically. No domain needed.

## Notes
- Data is stored locally in your browser (API key, addresses, signatures, delivered status). Photos are **not persisted**.
- Max route size: **25 total points** (origin + waypoints + destination) — this is a Google Directions limit.
- If you see a blank map, make sure your API key is valid and that those 3 APIs are enabled.
- For phone capture, use the **“Add photo”** button in the manifest rows.

— Built 2025-08-27
