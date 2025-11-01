# Software-Website

A simple static marketing website built with plain HTML and CSS. This repository contains a lightweight site layout for a software company, including a header, multiple content sections, and a contact form layout.

## Contents

- `index.html` — main HTML page.
- `assets/css/` — stylesheets (reset, base, and `style.css`).
- `assets/images/` — images used by the site.
- `assets/videos/` — embedded or referenced videos.

## Quick preview (Local)

You can preview the site locally by opening `index.html` directly in a browser, or better, serve it with a small static server to avoid CORS issues with some browsers:

Or click this link: https://tthphat.github.io/Software-Website/

## Project structure / notes

- CSS is in `assets/css/style.css`. The site uses CSS variables for colors and layout helpers in `base.css`.
- Header uses flexbox and `position: sticky; top: 0` for a fixed-on-scroll effect.
- Section layouts mix CSS Grid and Flexbox. See comments in `style.css` for per-section notes.

## Troubleshooting

- Sticky header not working: ensure `top: 0` is set and no ancestor has `overflow` or `transform` that creates a new containing block.
- Grid/spacing issues: `gap` applies only to direct children of a grid/flex container — reset child margins if spacing looks off.

---
