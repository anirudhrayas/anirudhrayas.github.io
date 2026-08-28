# Anirudh Rayas Personal Website

Source for [anirudhrayas.github.io](https://anirudhrayas.github.io), built with Jekyll and the al-folio theme.

## Local Build

```bash
bundle install
bundle exec jekyll build
```

## Deployment

GitHub Actions builds the site from `main` or `master` using `.github/workflows/deploy.yml` and deploys the generated `_site` folder to GitHub Pages.
