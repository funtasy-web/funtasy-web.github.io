# funtasymedia.com

The marketing site for **Funtasy Media** — a boutique social-media representation studio for digital-first talent. It's a single, self-contained static page served by GitHub Pages.

## Structure

- **`index.html`** — the entire site. Self-contained: inline CSS, inline SVG (the monogram), and a small progressive-enhancement script for the scroll reveals. No build step, no dependencies.
- **`favicon.svg`** — the monogram favicon.
- **`CNAME`** — the custom domain (`funtasymedia.com`); GitHub Pages reads this.
- **`brand/`** — source logo assets (mark, wordmark, lockup as transparent PNG/TIFF + SVG). Git-ignored by default.

## Editing & preview

Open `index.html` directly in any browser to preview — there is no build process. Make changes, commit, and push to `main`; GitHub Pages redeploys automatically.

## Design notes

- **Type:** Futura (wordmark, hero, headings) + Avenir Next (body, labels).
- **Palette:** white / cool grey neutrals, near-black ink, one restrained slate-blue accent (`#3A5A7C`).
- **Logo:** an "F" set inside camera viewfinder brackets — a quiet nod to framing the talent the studio represents.

## Hosting

Served by GitHub Pages from this repository's default branch, mapped to `funtasymedia.com` (apex) with `www` redirecting to it.
