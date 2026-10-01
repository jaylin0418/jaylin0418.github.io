# jaylin0418.github.io

Jie Lin's personal academic website, built with [al-folio](https://github.com/alshedivat/al-folio).

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000/.

## Deployment

Pushes to `main` trigger `.github/workflows/deploy.yml`, which builds the site
with Jekyll and publishes the result to the `gh-pages` branch. In the repo's
**Settings → Pages**, set the source branch to `gh-pages`.

## Content

- `_pages/about.md` — bio and profile
- `_news/` — short announcements shown on the about page and `/news/`
- `_bibliography/papers.bib` — publications (BibTeX)
- `_pages/teaching.md` — teaching assistant experience
- `_data/socials.yml` — contact / social links
