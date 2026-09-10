# AI3D Foundation

Static GitHub Pages site for `ai3d.foundation`.

## Content

The hero remains in `index.html`. The four main chapters are loaded at runtime from Markdown files in `md/`:

- `md/what-we-mean-by-3d.md`
- `md/research.md`
- `md/work.md`
- `md/why-independent.md`

`index.html` fetches these files and renders them with Marked. GitHub Pages serves the Markdown files as ordinary static assets, so no build step is required.

## Logo

The supplied square logo is preserved in `assets/` as two layout-specific crops:

- `assets/ai3d-mark.png` for the masthead
- `assets/ai3d-foundation.png` for the footer

## Local preview

Because the page uses `fetch()`, preview it through a local HTTP server rather than opening `index.html` directly as a `file://` URL.

```bash
python3 -m http.server 8000
```
