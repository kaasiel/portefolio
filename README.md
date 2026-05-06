Portfolio Project — Overview
===========================

**Project summary**
- **Description:** This repository contains static portfolio/demo websites and template projects (HTML/CSS/JS) collected or created as part of a portfolio. Each subfolder holds a standalone site with its own assets and styles.

**How to view**
- Open any index.html in a browser (double-click or use a Live Server). No build step required — these are static HTML sites.

**Top-level files**
- **documentation.html:** Project-level documentation or notes (if present).
- **index.html:** A potential root portfolio landing page (if present at root).
- **style.css:** Root stylesheet used by the root `index.html` (if referenced).

**Top-level folders**
- **sakafo2/**: A site (likely food/restaurant themed).
  - Contains its own `index.html`, `css/` (styles including `all.css`, `style.css`, `responsive.css`), `js/` (AOS, Bootstrap, jQuery), `img/` and fonts (`cookie-monster-font/`, `super-shape-font/`, `fontawesome/`).
  - Includes FontAwesome assets under `fontawesome/` (CSS, JS, webfonts) and AOS animation support.

- **site-commerce/**: Small e-commerce demo or template.
  - Has `index.html`, `css/` (stylesheets like `style1.css`, `style2.css`), `image/`, `js/` and FontAwesome assets.

- **taxi-site/**: Taxi/transport themed site template.
  - Contains `index.html`, `css/` (including `kasiel.css` and AOS), `image/`, `js/` and FontAwesome assets.

**Common technologies & libraries used**
- **HTML/CSS/JS:** Static site structure.
- **Bootstrap:** Present as `bootstrap.min.css`/`bootstrap.min.js` in some folders.
- **AOS (Animate on Scroll):** Present as `aos.css`/`aos.js` for scrolling animations.
- **jQuery:** `jquery.min.js` is included where needed.
- **FontAwesome:** Local copy included in subfolders under `fontawesome/` for icons.

**Assets & Fonts**
- Each site keeps images under `img/` or `image/` and fonts under dedicated folders (e.g., `cookie-monster-font/`, `super-shape-font/`). There are also `webfonts/` under `fontawesome/`.

**Development notes & suggestions**
- These are static templates — to run locally, open `index.html` files in a browser. For live-reload while developing, use VS Code Live Server or a simple HTTP server (for example: `python3 -m http.server 8000`).
- If you plan to combine sites or extract components, standardize CSS variables and reorganize shared `js/` and `css/` into a central `assets/` folder.

**Credits & licenses**
- FontAwesome files include `LICENSE.txt` inside their folders — please follow FontAwesome licensing when publishing.
- Any third-party fonts or scripts included in `cookie-monster-font/`, `super-shape-font/`, or other asset folders should be checked individually for license terms.

**Where to go next**
- Update this README with any project-specific goals (which site is the portfolio entry, which files are drafts, etc.).
- If you want, I can:
  - Add a short preview screenshot for each site,
  - Add a small script to serve all sites and a single index listing,
  - Or generate a CONTRIBUTING guide for future edits.

---
Generated on 2026-05-06
