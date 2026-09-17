# NAZZTEC Website Redesign — UAT

Homepage design concepts for NAZZTEC's corporate website redesign, built for client review before a full Webflow build. Three visual directions are being prepared so the client can compare approaches and pick one to move forward with.

NAZZTEC is a technology consulting company (cybersecurity, cloud, managed services, digital transformation, staff augmentation) operating out of India, Saudi Arabia, and the United States. This project repositions their web presence to read as an enterprise consultancy rather than a generic IT vendor.

## Live previews

- **Demo 1 — Bold Tech Enterprise**: [`index.html`](./index.html) — live at https://annu-rai.github.io/nazztec-website-uat/
  Full-bleed photography hero, alternating dark/light sections, colorful gradient art, icon-badge card grids. Inspired by Slalom, PwC, Kyndryl, Accenture, and Infosys.
- **Demo 2 — Editorial Authority**: [`demo2.html`](./demo2.html) — live at https://annu-rai.github.io/nazztec-website-uat/demo2.html
  Predominantly white/cream, bold black serif headlines, a single blue accent used as diagonal flag shapes and sharp-cornered buttons, arrow-links instead of card grids. Inspired by PwC's editorial consulting style.
- **Demo 3** — not yet built.

Each demo carries a small banner linking to the other so the client can flip between them while reviewing.

## Contents

- **`index.html`** / **`demo2.html`** — the two homepage concepts described above, using identical NAZZTEC content (services, locations, staffing, frameworks, etc.) with different visual systems.
- **`docs/project-brief.html`** — a one-page project brief covering scope, design rationale, and next steps.
- **`docs/webflow-spec.html`** — the implementation spec for rebuilding Demo 1 in Webflow: Client-First class naming for every component, CMS collection schemas (Services, Locations, Insights), interaction mapping, and build order. (Written against Demo 1 — update if a different demo is chosen.)

## Design systems

**Demo 1 — Bold Tech Enterprise**
- Type: Fraunces (display), Public Sans (body), IBM Plex Mono (data/reference codes)
- Color: brand blue `#17457F`, ink `#0E1B2B`, signal accent `#0FAFC4`, slate `#5C6B78`
- Layout: full-bleed photography hero, alternating dark/light sections, icon-badge card grids, fixed side-rail section nav

**Demo 2 — Editorial Authority**
- Type: Fraunces (bold serif display), Public Sans (body), IBM Plex Mono (labels)
- Color: near-black ink `#14181F`, white/cream `#FFFFFF` / `#FAF6F0`, single brand-blue accent `#17457F`
- Layout: asymmetric text+image splits, diagonal flag motif over photography, arrow-links in place of cards, sharp corners throughout, no dark sections except footer/CTA

## Status

Design concept stage — pending client sign-off on a direction before the Webflow build begins. The Industries section and several content areas (About, Careers, Insights) are explicitly marked as placeholders pending client input in both demos.
