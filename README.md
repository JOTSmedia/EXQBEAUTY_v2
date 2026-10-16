# Exquisite Beauty — v2

Animated redesign of exqbeauty.com: WebGL beach hero, rotating 3D product models, all-caps body type, Forum wordmark type.

## Upload to GitHub Pages
1. Create a new repository and upload **everything inside this folder** (`index.html`, `assets/`, `.nojekyll`), not the `_v2` folder itself.
2. Repo Settings > Pages > Deploy from branch > `main` / root.
3. Open the Pages URL after a minute.

## Notes
- Must be served over http(s). Opening `index.html` by double-click will not load the 3D or the hero shader (browsers block modules and textures on `file://`). To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
- Libraries load from CDNs (three.js 0.160.0, GSAP 3.12.5) and fonts from Google Fonts (Forum, Poppins), so the page needs an internet connection.
- The cart is a front-end demo. Checkout and service links point to exqbeauty.com.

## Files
- `index.html` — the whole site (HTML, CSS, JS)
- `assets/hero.jpg` — beach photo used by the animated hero
- `assets/sourcing.jpg`, `assets/styling.jpg` — service photos from the original site
