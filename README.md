# Zentitech

Marketing website for **Zentitech** — *We turn AI ambition into shipped outcomes.*

AI Video · Strategic Consulting · Delivery

## Project structure

```
.
├── index.html              # Home page (entry point)
├── README.md
├── assets/                 # Static assets
│   ├── css/
│   │   └── styles.css      # Shared styles
│   ├── pdf/
│   │   └── zentitech-brochure.pdf
│   └── img/                # (add images here)
└── pages/                  # Sub-pages
    ├── consulting.html
    ├── delivery.html
    ├── video.html
    ├── accelerator.html
    └── zentitech-brochure.html
```

### Conventions for expanding the site

- **New page** → add to `pages/`. Link its stylesheet as `../assets/css/styles.css` and link home as `../index.html`.
- **New asset** → put CSS in `assets/css/`, images in `assets/img/`, downloads in `assets/pdf/`.
- **From `index.html`** (root) → reference sub-pages as `pages/…` and assets as `assets/…`.
- The brochure PDF is downloadable from the home page's **Get started** (contact) section.

## Run locally

Static site — serve the folder from the repo root:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Live site

Published via GitHub Pages from the `main` branch (root). See repository **Settings → Pages**.
Live at: https://shenhao-practice.github.io/zentitech/
