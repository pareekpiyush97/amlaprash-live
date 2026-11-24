# ChoKho Chhe — Amlaprash

Single-product marketing site for **ChoKho Chhe Amlaprash** (a Jadi & Buty product) — a pure
Ayurvedic amla preserve. Built from the approved design mockup.

*Asli hai, isliye aasan hai.* — Recipe from Bikaner · Made in Sitapura, Jaipur.

## Stack
- Static HTML / CSS / vanilla JS (single `index.html`, self-contained)
- GSAP + ScrollTrigger (CDN) for scroll reveals and the sticky quick-add bar
- Brand artwork (jar, mascots Golu & Mishti, label) extracted from the design mockup
- Google Fonts: Inter (Latin) + Mukta (Devanagari)

## Sections
Hero · The Story (4 scenes) · Product (size / qty / cart / accordions) ·
45-ingredient formulation table · Origin timeline · Trust · Reviews · FAQ ·
Final CTA · Contact form · Footer. Includes a working client-side cart drawer and sticky quick-add bar.

## Notes / to wire up
- **Prices** (₹299 / ₹649 / ₹1199) are placeholders — connect to the ChoKho Chhe Shopify store.
- **Checkout** and **Buy it now** are stubbed to an alert — point them at Shopify cart permalinks / variant IDs.
- **Reviews** are sample copy — swap for the live review-app feed.
- **Contact form** has no backend — connect to an email/Formspree/Shopify endpoint.

## Run locally
Open `index.html` in a browser, or serve the folder: `python3 -m http.server`.
