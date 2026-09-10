# AI3D Foundation

Static GitHub Pages site for [`ai3d.foundation`](https://ai3d.foundation).

## Structure

The site is authored as static HTML with one shared stylesheet:

- `index.html` — homepage thesis and work areas
- `research/index.html` — curated research lineage
- `publications/index.html` — selected bibliographic record
- `field-building/index.html` — community and field-building work
- `styles.css` — shared editorial layout and responsive styles

Core content is present in the delivered HTML. The site has no runtime JavaScript or client-side Markdown dependency.

## Logo

The supplied square logo is preserved in `assets/` as two layout-specific crops:

- `assets/ai3d-mark.png` for the masthead and favicon
- `assets/ai3d-foundation.png` for the footer and social preview

## Local preview

Serve the repository root over HTTP so root-relative links behave as they do on GitHub Pages:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
