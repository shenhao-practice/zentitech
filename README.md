# Zentitech

Marketing website for **Zentitech** — *We turn AI ambition into shipped outcomes.*

AI Video · Strategic Consulting · Delivery

## About Zentitech

Zentitech helps organisations turn AI ambition into real, shipped outcomes. Most AI
pilots never reach production — we close that gap. We decide where AI actually wins,
turn the strategy into software you own, and leave your team with the assets and
enablement to keep going. Low-risk phases, and you own everything we build.

### What we do

- **Strategic Consulting** — We help leadership find the opportunities that truly move
  the needle, and leave you with a prioritised, costed roadmap and a clear path from
  pilot to production.
- **Delivery** — We build, integrate, and harden the working system, then hand it over
  with the documentation your team needs to run it — built to last, with agentic
  automation, and yours to own.
- **AI Video** — Powered by Seedance, our pipeline turns a brief into broadcast-ready
  cuts (text-to-video and image-to-video), produced at volume without losing creative
  control — brand-consistent, human-in-the-loop, with economics that improve over time.
- **Accelerator** — A fast, repeatable programme that packages strategy, delivery, and
  creative into reusable assets, playbooks, and enablement — making AI a standing
  capability, not a one-off project.

### How we work

Short, outcome-based phases, each ending with something you can use and a gate where you
decide whether to continue: **Discover → Frame → Prototype → Build → Scale.**

**Get in touch:** [info@zentitech.com](mailto:info@zentitech.com)

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
