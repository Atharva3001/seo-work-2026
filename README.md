# atharva-portfolio

Personal portfolio site for Atharva Tuljapurkar — Sr. SEO Analyst based in Pune.

🔗 **Live:** [your-domain.com](https://your-domain.com)

## About

Single-page editorial portfolio covering work, approach, and selected case studies across D2C apparel, legacy ayurvedic wellness, and enterprise luggage brands.

Built as a single static HTML file. No build step, no framework, no dependencies.

## Stack

- Plain HTML + CSS (no framework)
- Google Fonts: Fraunces, Newsreader, JetBrains Mono
- Vanilla JS for scroll-reveal (IntersectionObserver)

## Running locally

```bash
# Clone
git clone https://github.com/your-username/atharva-portfolio.git
cd atharva-portfolio

# Open in browser
open portfolio.html
# or serve with any static server, e.g.
python3 -m http.server 8000
```

Then visit `http://localhost:8000/portfolio.html`.

## Deployment

Hosted on [Netlify / Vercel / GitHub Pages — pick one and replace this line]. Auto-deploys on push to `main`.

### GitHub Pages

1. Repo → Settings → Pages
2. Source: `Deploy from a branch` → `main` → `/ (root)`
3. Rename `portfolio.html` to `index.html` (or add a redirect)

### Netlify

Drop the folder into Netlify's deploy UI, or connect the repo. No build command needed — set publish directory to root.

## Structure

```
.
├── portfolio.html    # the entire site
└── README.md
```

## Updating content

All copy lives inside `portfolio.html`. Sections are clearly commented:

- `<!-- HERO -->`
- `<!-- ABOUT -->`
- `<!-- WORK -->` (case studies)
- `<!-- TOOLKIT -->` (Approach section)

Colors are defined as CSS custom properties at the top of the `<style>` block (`:root`) — change once, applies everywhere.

## License

Personal portfolio. Code is open for reference, content is not.

---

© 2026 Atharva Tuljapurkar · Pune, India
