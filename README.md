# Tania St Vil — Portfolio

Personal portfolio site built with plain HTML, CSS, and JavaScript — no build step, no dependencies. Light neumorphic style.

**Live:** https://thany-8.github.io

## Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Structure

```
├── index.html               # main page (all sections)
├── blog-personal.html       # blog article pages
├── blog-professional.html
├── blog-hobby.html
├── assets/
│   ├── css/style.css        # theme + layout
│   ├── js/main.js           # menu, tabs, scroll-spy, animations
│   ├── images/              # photos, logos/, blog/ covers
│   └── Tania-St-Vil-Resume.pdf
└── README.md
```

## Change the accent color

Edit the top of `assets/css/style.css`:

```css
--color-primary: #ff014f;
--color-subtitle: #f9004d;
```

## Deploy

Hosted on GitHub Pages — pushing to `main` auto-deploys to the live URL above.
