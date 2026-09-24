# ARCHIVE

**Curated vintage & pre-loved fashion marketplace** — authenticated pieces, editorial catalogue, and a scroll-driven landing experience.

**Live:** [tanmays0.github.io/ARCHIVE](https://tanmays0.github.io/ARCHIVE/)

> Independent demo storefront. Not affiliated with Nike, Jordan, or any listed brand.

---

## What it is

ARCHIVE is a static multi-page e-commerce demo for a **multi-brand resale** shop:

- Hero **scrollytelling** (canvas + GSAP / ScrollTrigger / Lenis)
- Full shop flows: browse, PDP, cart, checkout, auth/profile, orders, wishlist
- Catalogue with **brand, condition, era, authenticated** fields and single-unit listings
- Design system: **Fraunces** + **General Sans**, warm-neutral palette (bone / ink / stone / clay)

Evolved from an earlier Nike commercial / Velocity Athletics concept into ARCHIVE via rebrand + catalogue transformation (mechanics kept; brand/copy/tokens updated). See `CHANGELOG.md` and `REBRAND-AUDIT.md`.

---

## Stack

| Layer | Choice |
|--------|--------|
| Markup | Vanilla HTML (MPA) |
| Styles | Hand-authored CSS + design tokens |
| Logic | Vanilla JS (cart, catalog, shell) |
| Motion | GSAP, ScrollTrigger, Lenis (CDN) |
| Data | Generated product catalog (`js/products-catalog.generated.js`) |
| Deploy | GitHub Pages |

No React/Next bundler — files serve as authored.

---

## Local

```bash
npm install
npm start
```

Opens a local static server (see `scripts/start-dev.js` / `serve`).

---

## Repo map (high level)

```
index.html          # Landing + tiger/cheetah scrollytelling hero
shop*.html          # Category & listing pages
product*.html       # Product detail
cart.html / checkout.html / …
css/                # Design system + styles
js/                 # Catalog, cart, shell, animations
tigerimages/        # Hero frame sequence
scripts/            # Catalog generation, verify-rebrand, etc.
```

---

## Author

[Tanmay Shinde](https://github.com/tanmays0) · [LinkedIn](https://www.linkedin.com/in/tanmay-shinde-160a60282/)
