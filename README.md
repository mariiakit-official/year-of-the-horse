# The Year of the Horse — A Life in Ten Chapters

A standalone, responsive personal-storytelling website for GitHub Pages. It covers all **10 required years** (2025, 2026, 2027, 2028, 2029, 2034, 2039, 2044, 2049, and 2054) with a **year title, symbolic illustration, fortune, and reflection** for each year.

## Deploy to GitHub Pages

1. Create a **new public GitHub repository** (for example, `year-of-the-horse`).
2. Upload **the contents of this folder** to the repository's root. The `index.html` file must be in the root, next to `styles.css`, `script.js`, and `assets/`.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then save.
6. Your website will normally appear at `https://YOUR-USERNAME.github.io/year-of-the-horse/` if you use that repository name. The exact link depends on your username and repo name.

Alternatively, add files locally and push via Git. No build step, dependencies, API keys, or external hosting is needed.

## Customization

- Edit the `chapters` array in `script.js` to revise fortunes, reflections, or goals.
- Change layout/design in `styles.css`.
- Replace an illustration by overwriting `assets/YEAR.webp` with a new image of the same filename.
- Future events are written as **hopes and visions**, not accomplished historical facts.

## Features

- Fully static GitHub Pages-ready HTML/CSS/JavaScript
- Responsive desktop/mobile grid and timeline filters
- Accessible chapter dialog with keyboard support (Esc, Left/Right arrows)
- Optimized WebP illustrations; no external scripts, tracking, or fonts
- Reduced-motion support and semantic page structure

**Privacy note:** The story is written for public display. Review personal details before publishing. The text avoids contact details and precise locations.
