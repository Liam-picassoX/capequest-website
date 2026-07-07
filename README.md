# CapeQuest — Promo Website

A single-page promotional website / ad for **CapeQuest**, the Cape Town travel app.
The Mother City in your pocket: hidden gems, AI itineraries, bookable experiences and
the best of Cape Town under R200.

## Design

- **Inspiration:** [ApeChain on Awwwards](https://www.awwwards.com/sites/apechain) —
  bold monochromatic world, oversized display typography, marquees, playful
  hover/scroll interactions and a gamified, community-first feel.
- **Brand palette** (taken directly from the CapeQuest app's `ThemeContext`):

  | Token    | Hex       | Usage                     |
  |----------|-----------|---------------------------|
  | bg       | `#07111F` | Deep navy background      |
  | surface  | `#0D1E35` | Cards, nav, phone mockup  |
  | border   | `#1E3A5F` | Borders and dividers      |
  | text     | `#D0E8FF` | Body text                 |
  | accent   | `#00C896` | Brand green, CTAs         |
  | headline | `#f5e6c8` | Cream display headlines   |
  | tagline  | `#1a7fa8` | Ocean-blue section labels |

- **Type:** Archivo Black (display) + Space Grotesk (body), via Google Fonts.

## Motion & interaction

Built with [GSAP](https://gsap.com) (ScrollTrigger) + [Lenis](https://lenis.darkroom.engineering)
smooth scroll, all loaded from CDN:

- Preloader with counter and staggered letter reveal
- Hero image window that zooms to fullscreen on scroll (pinned, scrubbed clip-path)
- Pinned horizontal-scroll photo gallery with per-card parallax
- Feature rows with green flood hover + cursor-following image previews
- Custom cursor, magnetic buttons, masked line-reveal titles, scroll-reactive nav
- Falls back gracefully: `prefers-reduced-motion`, hidden tabs, or a blocked CDN
  all get instant static content.

## Photography

All imagery is real Cape Town, hotlinked from free sources:

- Aerial Table Mountain & stadium, Camps Bay, Bloubergstrand sunset — [Unsplash](https://unsplash.com)
- Bo-Kaap houses, Boulders Beach penguins, Lion's Head at dusk — [Wikimedia Commons](https://commons.wikimedia.org)

## Run it

No build step — it's one static file.

```bash
# open directly
start index.html

# or serve it
npx serve .
```

## Companion video ad

A 30-second video ad in the same brand style was generated with [Motion](https://motion.so)
using the same Cape Town photography and palette.
