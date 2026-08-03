# Melvin's A/C &amp; Heating — Demo Site

A demo marketing website built for **Melvin's A/C Heating of Tampa LLC** (styled *Melvin's A/C &amp; Heating*), a local HVAC business in Ruskin / South Hillsborough, FL. Built as a demo-first sales pitch by Wilson Innovations.

## Business
- **Trade:** HVAC — A/C repair, heating repair, honest repair-vs-replace guidance, new system installation when truly needed
- **Area:** Ruskin &amp; South Hillsborough, FL
- **Phone:** (813) 263-6503
- **Address:** 103 SW 11th Ave, Ruskin, FL 33570
- **Hours:** Open 24 hours, 7 days
- **Reputation:** 4.4★ / 49 Google reviews; loyal snowbird clientele; fixes what can be fixed and doesn't push new units.

## Design
- **Fonts:** Amiko (display, 600/700) + Lato (body) via Google Fonts
- **Palette:** glacier white, steel blue, warm red accent — an honest, neighborhood-HVAC feel
- Single-page, fully responsive, semantic HTML with AA-contrast color, alt text, reduced-motion-aware reveals, lazy-loaded imagery
- Sticky header with an always-visible call button (no fixed bottom call bar)
- LocalBusiness (`HVACBusiness`) JSON-LD structured data
- Works directly from `file://`

## Sections
Hero · trust bar · services · repair-vs-replace feature · pull-quote divider · testimonials (real Google reviews) · homeowners/snowbird note · hours &amp; service area · call-to-action band · footer.

## Demo notes
- Ships with `<meta name="robots" content="noindex">` — **remove the noindex tag when the site goes live** (marked with a comment in `index.html`).
- Open Graph / Twitter Card tags use absolute URLs pointing at the GitHub Pages host.
- No contact forms, no prices, no invented facts (no emails, license numbers, or founding years).
- Imagery: topical HVAC photography from Unsplash.

## Deploy
Static site — a single `index.html`. Hosted on GitHub Pages from the `master` branch (root).

---
Website by [Wilson Innovations](https://wilsoninnovations.net)
