# Poorvi Acharya — Jekyll academic site

A clean, typography-forward academic site built with Jekyll. Three cohesive pages
share fonts, palette, nav, data-driven content, and card styling:

- **About** (`/`) — leads with research identity, a research teaser card, a
  "lived relationship with language" panel, and a news momentum timeline.
- **Research** (`/research/`) — art-portfolio card grid: one featured project
  plus a two-up grid, each with a custom visual, venue tag, title, and hook.
- **Publications** (`/publications/`) — citable papers and preprints rendered
  from structured YAML data.

## Structure

```
_config.yml                  Site config (kramdown + sass)
_data/projects.yml           Project cards (title, hook, venue, accent, visual)
_data/characters.yml         Data for the Chinese-character visual
_data/news.yml               News timeline entries (About page)
_data/publications.yml       Publications list data
_layouts/default.html        HTML shell, fonts, Font Awesome, nav, metadata
_includes/nav.html           Shared primary nav (About · Research · Publications)
_includes/project-card.html  Reusable card, loops over project data
_includes/visuals/           syntax-tree · character-grid · error-json
assets/css/main.scss         Design tokens + component styles
images/                      Headshot plus favicon and app icon assets
index.md                     About page (Markdown + Liquid)
research.md                  Research page (Markdown + Liquid)
publications.md              Publications page (Markdown + Liquid)
```

## Run locally

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

The nested `personal-website-2/` app is retained only as the original Next.js
reference implementation and is excluded from the root Jekyll build.

## Editing content

- **Projects:** add or reorder in `_data/projects.yml`. Set `featured: true`
  for the large side-by-side card. `accent` is `p1` (slate blue), `p2` (clay),
  or `p3` (sage). `visual` maps to `_includes/visuals/<visual>.html`.
- **News:** edit `_data/news.yml` (`label` + `text`, newest first).
- **Publications:** edit `_data/publications.yml`.
- **Languages / bio:** edit directly in `index.md`.
- **Nav links:** edit `_includes/nav.html`.
