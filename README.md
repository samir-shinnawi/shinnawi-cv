# Samir Shinnawi — CV site

Single static page. No build step.

- `index.html` — the whole site (CSS + content + animation inline).
- Animation: [Motion](https://motion.dev) v13.4.4, loaded as UMD from jsDelivr (`window.Motion`): `animate`, `stagger`, `inView`, `scroll`, `hover`.
- Fonts: Fraunces, IBM Plex Sans, IBM Plex Mono via Google Fonts.

Open `index.html` directly, or host the folder on any static host (GitHub Pages, Vercel, Netlify).

To update content, edit the sections in `index.html`; each CV section is a `<section class="section" id="...">` block.
