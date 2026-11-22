# SpeedCheck Pro

A free internet speed test site, live at https://speedcheckpro.github.io/.

## What it is

SpeedCheck Pro measures real ping, download and upload speeds in the visitor's browser using Cloudflare test endpoints, and explains the results in plain English. No sign-up, no app, no estimated or placeholder numbers — every figure shown is a real measurement.

## Contents

- `index.html` — homepage with the working speed test widget, explainer sections, tool cards, all 20 guide cards and an FAQ.
- `tools/` — Speed Test, Ping Test, Download Time Calculator, Speed Requirements Checker.
- `guides/` — 20 original guides on internet speed, Wi-Fi, gaming, streaming and more.
- `images/` — featured images for the guides.
- `about.html`, `contact.html`, `privacy.html`, `disclaimer.html` — legal and information pages.
- `sitemap.xml`, `robots.txt`, `favicon.svg`, `.nojekyll`.

## Notes

- The speed test downloads and uploads real test data; a full test can use a few hundred MB, so the homepage warns mobile users to use Wi-Fi.
- Static site — no build step and no server code. Deploy the folder contents to GitHub Pages as-is.
