# Design Essentials — Gallery Minimal Colour Variants

This package preserves the structure of the previously selected fifth mockup and presents five alternative colour palettes.

## Routes

- `1/` — Warm Ivory / Bronze
- `2/` — Midnight Navy / Champagne
- `3/` — Forest Green / Linen
- `4/` — Terracotta / Bone
- `5/` — Stone Taupe / Oxblood

Each route contains:

- `index.html`
- `projects.html`
- `contact.html`
- `theme.css`

Shared structural styling is stored in `common.css`. The only visual differences between variants are CSS custom properties inside each `theme.css`.

## Run locally

From this folder:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Notes

- Pure HTML and CSS; no JavaScript.
- The mobile menu uses a CSS-only checkbox pattern.
- The logo is packaged locally.
- Mockup photographs load from Unsplash and should be replaced by the client's original project photographs before production.
- The form is visual only until connected to a backend or form service.
