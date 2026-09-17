# NAZZTEC Website Redesign — UAT

Homepage design concepts for NAZZTEC's corporate website redesign, built for client review before a full Webflow build. Three visual directions are being prepared so the client can compare approaches and pick one to move forward with.

NAZZTEC is a technology consulting company (cybersecurity, cloud, managed services, digital transformation, staff augmentation) operating out of India, Saudi Arabia, and the United States. This project repositions their web presence to read as an enterprise consultancy rather than a generic IT vendor.

## Live previews — three separate URLs

- **Demo 1 — Bold Tech Enterprise**: https://annu-rai.github.io/nazztec-website-uat/ ([`index.html`](./index.html))
  Full-bleed photography hero, alternating dark/light sections, colorful gradient art, icon-badge card grids. Inspired by Slalom, PwC, Kyndryl, Accenture, and Infosys.
- **Demo 2 — Editorial Authority**: https://annu-rai.github.io/nazztec-website-uat/demo2.html ([`demo2.html`](./demo2.html))
  Predominantly white/cream, bold black serif headlines, a single blue accent used as diagonal flag shapes and sharp-cornered buttons, arrow-links instead of card grids. Inspired by PwC's editorial consulting style.
- **Demo 3 — Bold Statement**: https://annu-rai.github.io/nazztec-website-uat/demo3.html ([`demo3.html`](./demo3.html))
  Near-black throughout, massive oversized uppercase headlines with one italic-serif accent word per heading, a single vivid cyan accent, pill buttons, flat hairline-divided lists instead of boxed cards. Inspired by Accenture and Slalom.

Each demo is a fully independent page/URL. A small banner at the top of each links to the other two, so the client can flip between them while reviewing — the banners themselves aren't part of any design and won't appear in the final build.

## Contents

- **`index.html`** / **`demo2.html`** / **`demo3.html`** — the three homepage concepts described above, using identical NAZZTEC content (services, locations, staffing, frameworks, etc.) with three different visual systems, for a fair side-by-side comparison.
- **`docs/project-brief.html`** — a one-page project brief covering scope, design rationale, and next steps.
- **`docs/webflow-spec.html`** — the implementation spec for rebuilding Demo 1 in Webflow: Client-First class naming for every component, CMS collection schemas (Services, Locations, Insights), interaction mapping, and build order. (Written against Demo 1 — update once the client picks a direction.)

## Design systems

**Demo 1 — Bold Tech Enterprise**
- Type: Fraunces (display), Public Sans (body), IBM Plex Mono (data/reference codes)
- Color: brand blue `#17457F`, ink `#0E1B2B`, signal accent `#0FAFC4`, slate `#5C6B78`
- Layout: full-bleed photography hero, alternating dark/light sections, icon-badge card grids, fixed side-rail section nav

**Demo 2 — Editorial Authority**
- Type: Fraunces (bold serif display), Public Sans (body), IBM Plex Mono (labels)
- Color: near-black ink `#14181F`, white/cream `#FFFFFF` / `#FAF6F0`, single brand-blue accent `#17457F`
- Layout: asymmetric text+image splits, diagonal flag motif over photography, arrow-links in place of cards, sharp corners throughout, no dark sections except footer/CTA

**Demo 3 — Bold Statement**
- Type: Public Sans (huge bold uppercase display + body), Fraunces italic (single accent word per heading), IBM Plex Mono (labels)
- Color: near-black `#0A0A0C` / panel `#141417`, vivid cyan accent `#17E0D6`, off-white text `#F2F2F0`
- Layout: massive typographic hero (no photography), flat hairline-divided feature lists instead of cards, pill buttons, minimal color usage outside the single accent

## Status

Design concept stage — pending client sign-off on one of the three directions before the Webflow build begins. The Industries section and several content areas (About, Careers, Insights) are explicitly marked as placeholders pending client input across all three demos.
