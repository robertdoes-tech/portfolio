# Marc Robert Tretasco: portfolio

A single-page portfolio site in plain HTML, CSS and JavaScript, with no build step.

## Preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

## Make it yours

Placeholders are in `[square brackets]` in `index.html`.

- **Projects:** each `<article class="work-card">` in the Work section is one project. Set `data-cat` to `design`, `writing`, `seo`, `social`, `web` or `ai` so the filter buttons work. To show a real image, put it in `assets/work/` and replace the `<div class="cover ...">` contents with `<img src="assets/work/your-image.jpg" alt="...">`.
- **Portrait:** put your photo at `assets/marc.jpg` and swap it in where the comment in the About section says.
- **Social links:** replace the `#` links in the Contact section, and add the same URLs to `sameAs` in the JSON-LD block in `<head>`.
- **Domain:** replace `https://example.com/` in `index.html`, `robots.txt` and `sitemap.xml` with your real domain, and add an `assets/og.png` share image (1200×630).

## Deploy

- **GitHub Pages:** Settings → Pages → Deploy from a branch → `main` / root.
- **Netlify or Vercel:** import the repo. There's no build command, and the publish directory is the repo root.
