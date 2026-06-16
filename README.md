# Bosen Tiling Website

A free, static business website for **Bosen Tiling** — a professional tile installation company. Hosted on [GitHub Pages](https://pages.github.com/) at no cost.

## Live site

After deployment is enabled, the site will be available at:

**https://chaxic.github.io/BosenTilingWebsite/**

## What's included

- Responsive single-page layout (mobile, tablet, desktop)
- Hero, services, process, portfolio gallery, testimonials, about, and contact sections
- Contact form (opens the visitor's email client)
- GitHub Actions workflow for automatic deployment on push to `main`

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Enable GitHub Pages

1. Merge this branch into `main` (or push directly to `main`).
2. In the GitHub repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. The workflow in `.github/workflows/pages.yml` will deploy the site automatically.

## Customize

| Item | File / location |
|------|-----------------|
| Business name & copy | `index.html` |
| Colors & layout | `css/styles.css` |
| Phone, email, hours | Contact section in `index.html` |
| Portfolio images | Gallery section in `index.html` (replace Unsplash URLs with your own) |

Replace placeholder contact details (`(555) 123-4567`, `hello@bosentiling.com`) with your real business information before going live.

## License

Content and code in this repository are provided for the Bosen Tiling business website.
