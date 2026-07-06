# Le Salon — Atelier of Hair & Beauty, Kathmandu

Luxury single-page site for [Le Salon](https://www.instagram.com/lesalonnepal/) (@lesalonnepal), Kathmandu.

- **Design**: black + champagne-gold editorial identity built from the salon's logo; Italiana / Cormorant Garamond / Inter type stack.
- **3D hero**: Three.js "golden silk" — ~100 flowing hair-like light strands plus golden dust, with mouse parallax; recedes as you scroll.
- **Motion**: GSAP + ScrollTrigger reveals, Lenis smooth scroll, custom cursor, magnetic-feel hovers, animated counters, rotating SVG medallion.
- **No-fail fallbacks**: `HAS` / `MOTION` / `HAS3D` guards — the site is fully readable with no JS, no WebGL, or `prefers-reduced-motion`.
- **Self-contained**: GSAP, ScrollTrigger, Lenis and Three.js are vendored in `assets/vendor/`; CSP locked to `'self'` + Google Fonts.

## Structure

- `index.html` — everything (markup, styles, scripts inline)
- `assets/vendor/` — vendored libraries
- `.github/workflows/validate.yml` — HTML validation + internal link check on every push

Deployed via GitHub Pages from `main`.
