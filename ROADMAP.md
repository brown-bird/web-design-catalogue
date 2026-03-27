# Web Design Catalogue — Feature Roadmap

A living reference of all candidate styles for future additions.
Currently implemented: 16 styles (01–16).

---

## Currently Implemented

| # | Style | Status |
|---|-------|--------|
| 01 | Brutalism | ✅ Done |
| 02 | Glassmorphism | ✅ Done |
| 03 | Neomorphism | ✅ Done |
| 04 | Swiss / International | ✅ Done |
| 05 | Cyberpunk | ✅ Done |
| 06 | Minimalism | ✅ Done |
| 07 | Skeuomorphism | ✅ Done |
| 08 | Memphis / 80s | ✅ Done |
| 09 | Claymorphism | ✅ Done |
| 10 | Art Deco | ✅ Done |
| 11 | Bento Box | ✅ Done |
| 12 | Material Design | ✅ Done |
| 13 | Vaporwave | ✅ Done |
| 14 | Bauhaus | ✅ Done |
| 15 | Retrofuturism | ✅ Done |
| 16 | Broadsheet | ✅ Done |

---

## Tier 1 — Planned Next

*(All Tier 1 styles have been implemented.)*

---

## Tier 2 — Strong Candidates

Well-understood styles that would add variety, but some visual overlap risk with existing entries.

| Style | Description | Overlap Risk |
|-------|-------------|--------------|
| **Y2K / Retro Web** | Early 2000s web nostalgia: beveled buttons, star/flame cursor graphics, Comic Sans, marquee tags, under-construction GIFs. Clear era identity. | Low — distinct from all current entries |
| **Organic / Blob** | Asymmetric blob shapes as primary design element, soft gradients, flowing curves, no straight lines or sharp corners. Nature-inspired. | Low-medium — shares softness with Claymorphism |
| **Dark Academia** | Intellectual, gothic-adjacent: deep navy/brown, serif type, parchment textures, candlelight warmth, Victorian illustration aesthetics. | Low — nothing like it in catalogue |
| ~~**Retrofuturism**~~ | ~~Mid-century vision of the future: chrome, atomic starbursts, Populuxe curves, optimistic space age. Distinct from Cyberpunk (hopeful vs. dystopian).~~ | ✅ Implemented as style 15 |

---

## Tier 3 — Niche / Stretch

Interesting but harder to execute as a standalone web design style, or with narrower appeal.

| Style | Description | Challenge |
|-------|-------------|-----------|
| **Maximalism** | Everything everywhere all at once: layered textures, multiple competing typefaces, image collage, explicit rejection of negative space. | Hard to demonstrate without it looking broken |
| **Psychedelic / 60s** | Paisley patterns, rainbow gradients, Fillmore poster lettering, counter-culture imagery. | Narrow demographic, complex patterns |
| **Cottagecore** | Pastoral, handmade aesthetics: watercolour textures, botanical illustration, muted earth tones, handwritten fonts. | Hard to execute in pure CSS without texture images |

---

## Constraints

- **Static HTML/CSS only** — no build tools, frameworks, or JavaScript beyond the catalogue nav IntersectionObserver
- **Google Fonts only** — no external image CDNs, icon libraries, or other third-party assets
- Each style needs: preview section (index.html) + detail page (styles/[name].html + styles/[name].css)
