# Minku Kim — Academic Website

Personal academic website built with Jekyll and adapted from the
[Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme.

## Editing content

- Profile and site metadata: `_config.yml`
- Homepage copy: `index.md`
- Research entries: `_data/research.yml`
- Publication entries: `_data/publications.yml`
- Project entries: `_data/projects.yml`
- Honors and awards: `_data/awards.yml`
- Styling: `_sass/custom.scss`

Research and project preview images live in `assets/img/teasers`. Full media is
stored under `videos`, `images`, and `files`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` after the development server starts. GitHub Pages
builds and publishes the site automatically after changes are pushed to `main`.
