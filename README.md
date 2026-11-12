# Mirador

Mirador stops fake refund photos on second-hand marketplaces and food-delivery apps. When a buyer reports a damaged order, Mirador asks for a live photo, checks it in seconds and tells the platform whether to refund.

This repository holds the public site and an interactive demo:

- Three prepared cases: an honest buyer, an AI-edited photo, and a photo reused across accounts.
- "Try your own photo": real checks that run in the browser (capture timing, file metadata, reuse detection on the same device). Photos never leave the browser.

The site is a single `index.html` file with no build step, served with GitHub Pages.
