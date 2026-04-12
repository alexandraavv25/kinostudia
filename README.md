# KINOSTUDIAAA*

Website for KINOSTUDIAAA* — a studio concerned with the image.

## Structure

```
kinostudia/
├── index.html          — Portfolio / Landing page
├── about.html          — Manifesto
├── founder.html        — Founder bio
├── contact.html        — Contact form
├── publications.html   — Publications list
├── style.css           — All styles
└── assets/
    └── images/         — Place logo and image files here
```

## Setup

No build step required. Open `index.html` in a browser or deploy the folder directly to any static host (GitHub Pages, Netlify, Vercel).

### GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages → select `main` branch and `/ (root)` as source
3. Your site will be live at `https://yourusername.github.io/repo-name/`

### Custom Domain

Add a `CNAME` file to the root folder containing your domain:
```
kinostudiaaa.com
```

## Customization

### Content to fill in
- `founder.html` — Replace `[Founder Name]`, `[City, Country]`, and all bracketed fields
- `founder.html` — Add portrait image to `assets/images/` and update the `<img>` tag
- `index.html` — Replace placeholder portfolio items with real work
- `publications.html` — Replace placeholder items with real publications
- `contact.html` — Update email and Instagram handle
- All files — Update copyright year in footer

### Contact form
The form in `contact.html` requires a backend or form service. Recommended options:
- **Netlify Forms** — add `data-netlify="true"` to the `<form>` tag
- **Formspree** — change `action="#"` to `action="https://formspree.io/f/YOUR_ID"`

### Logo
To use the actual logo images, add them to `assets/images/` and replace the text logo in the nav:
```html
<!-- Replace this -->
<a href="index.html" class="nav-logo">KINOSTUDIAAA<span class="star">★</span></a>

<!-- With this -->
<a href="index.html"><img src="assets/images/logo-red.png" alt="KINOSTUDIAAA*" style="height: 18px;" /></a>
```

## Color Palette

| Name       | Hex       | Use                     |
|------------|-----------|-------------------------|
| Cream      | `#F0EDE4` | Background              |
| Red        | `#8B0000` | Brand, links, accents   |
| Dark       | `#1C1C1C` | Body text               |
| Mid        | `#7A746C` | Secondary text, labels  |
| Border     | `#D0C9BD` | Dividers, borders       |
