# Images to add

The site works and looks complete without these (the Ball Swinger preview and app
icon are drawn in CSS, and the favicon is an inline SVG). Add these only to polish
social sharing and iOS home-screen icons. Drop the files at the exact paths below.

| Path | Size | Format | Used by | Alt / notes |
|---|---|---|---|---|
| `assets/img/og.png` | 1200×630 | PNG/JPG | `og:image` on `index.html` | Social share card. Dark warm bg, "solmigo" wordmark + sun mark, tagline "Mobile app & game studio". |
| `assets/img/apple-touch-icon.png` | 180×180 | PNG | `apple-touch-icon` (both pages) | Solmigo sun mark on a warm dark rounded square (matches `favicon.svg`). |

## Optional upgrades
- **Real Ball Swinger screenshot** — replace the CSS `.phone-screen` block in `index.html`
  with `<img src="assets/img/ball-swinger.png" alt="Ball Swinger gameplay">` (portrait,
  ~800×1730). You already have the game's app icon at
  `~/Projects/Games/ball_swinger/assets/icons/playstore.png`.
- **App icon** — swap the `.app-icon` div for the real Ball Swinger icon the same way.

## Generation prompt (for og.png / icon)
> Minimal brand asset for "Solmigo", an indie mobile game studio. Warm near-black
> background (#231a10), a single amber-gold sun mark (#f2b64d) with clean rays,
> lowercase "solmigo" wordmark in Space Grotesk. Modern, restrained, premium.
> No gradients on text, no glassmorphism.
