# Philippe Lavoie — Personal Website

[![Live Site](https://img.shields.io/badge/live%20site-www.philippelavoie.com-blue)](https://www.philippelavoie.com)
[![Built with Jekyll](https://img.shields.io/badge/built%20with-Jekyll-red)](https://jekyllrb.com/)
[![Theme: Gradfolio](https://img.shields.io/badge/theme-Gradfolio-brightgreen)](https://github.com/jitinnair1/gradfolio)
[![Hosted on GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-black)](https://pages.github.com/)

Source code for my personal website at **[www.philippelavoie.com](https://www.philippelavoie.com)** — a space where I share my professional background, projects, and thoughts on tech leadership and team management.

---

## Website Sections

| Section | Path | Description |
|---------|------|-------------|
| **About** | `/` | Introduction — leader and engineering manager with 15+ years of experience building and engaging tech teams |
| **CV** | `/cv` | Professional history (Amilia, Nexapp, GSoft, Nmedia), education (B. Ing. Computer Engineering, Université de Sherbrooke), and key learning projects |
| **Projects** | `/projects` | Portfolio showcasing personal and professional projects |
| **Blog** | `/blog` | Articles on management, team culture, leadership practices, and more (8 posts, paginated) |

---

## Repository Structure

```
.
├── _config.yml          # Jekyll site configuration (title, URL, plugins, etc.)
├── index.md             # About / Home page
├── cv.md                # CV / Résumé page
├── archive.html         # Post archive page
├── blog/                # Blog index page
├── _posts/              # Blog posts (Markdown)
├── _projects/           # Portfolio project entries (Markdown)
├── _pages/              # Additional pages (projects gallery, 404)
├── _layouts/            # Page layout templates (default, about, post)
├── _includes/           # Reusable HTML components (nav, footer, analytics)
└── assets/              # CSS (SCSS) and images
```

---

## Tech Stack

- **Framework:** [Jekyll](https://jekyllrb.com/) (static site generator)
- **Theme:** [Gradfolio](https://github.com/jitinnair1/gradfolio) — responsive, dark-mode-ready Jekyll theme
- **Hosting:** [GitHub Pages](https://pages.github.com/) with a custom domain
- **Plugins:** `jekyll-seo-tag`, `jekyll-paginate`, `jekyll-email-protect`, `jekyll-target-blank`

---

## Local Development

Clone the repo and serve the site locally:

```bash
jekyll serve --incremental --trace
```

The site will be available at `http://localhost:4000/`. The `--incremental` flag rebuilds only changed files in real time; `--trace` helps debug any build errors.

---

## About Gradfolio

This site is built on [Gradfolio](https://github.com/jitinnair1/gradfolio), a responsive, dark-mode-ready Jekyll theme designed for personal websites and portfolios.

**Gradfolio features:**
- Responsive layout
- Respects the user's dark mode preference
- Projects page to showcase work and side projects

**Gradfolio is itself inspired by:**
- [hagura](https://github.com/sharu725/hagura)
- [al-folio](https://github.com/alshedivat/al-folio)
- [noir](https://github.com/essentialenemy/noir)
- [jekyll-TeXt-theme](https://github.com/kitian616/jekyll-TeXt-theme)

---

## License

MIT License

[![JekyllThemes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com)
