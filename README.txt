River Bridge Delivery — Single-File App (v12)
=================================================

What this is
------------
One `index.html` you can open locally or drop into Netlify Drop. No build step, no React, no Babel.

Highlights
----------
- Google Maps optimization (Distance Matrix + Directions)
- Delivered checkboxes w/ timestamps
- Signature capture (customer & driver)
- Photo proof per stop (compressed, included in print)
- Pricing rules:
  * Base: $20 + $2/mi after 5
  * Trailer: $30 base; $2/mi for first 5 miles; $3/mi after 5
  * + Pharmacy $10, + Rush $5, Extra stop fee, Tax %, Payment method, Logo URL
- Driver Mode + optional PIN
- Export CSV, Open in Google Maps, Print Invoice/Receipt
- Rates badge under Pricing Options for quick reference

How to deploy on Netlify Drop
-----------------------------
1) Go to https://app.netlify.com/drop
2) Drag-and-drop this `index.html` (or a folder that contains it).
3) Open the site URL Netlify gives you.
4) Paste your Google Maps API key → **Load Google Maps** → add addresses → **Optimize Route**.

Notes
-----
- Your API key, addresses, options, delivered status, and PIN are saved in your browser’s localStorage.
- Photos are NOT persisted; they live in memory and appear in the printout.
- The app respects your device timezone via toLocaleString().
