# Democracy and Political Violence Conference & Working Group — Website

Quarto website for the conference, hosted at Harvard University.

## Local development

```bash
quarto preview   # live reload at http://localhost:port
quarto render    # build to _site/
```

## Deployment

Pushing to `main` triggers a GitHub Action that renders the site and publishes it to the
`gh-pages` branch. Live at: https://cetialphafive.github.io/dpv-conference/

Set **Settings → Pages → Source = gh-pages branch** once after the first deploy.

## Structure

- `index.qmd` — landing page + listserv call-to-action
- `schedule.qmd` — full-day agenda
- `panels.qmd` — three main panels (chairs + papers)
- `posters.qmd` — poster session + submission form
- `about.qmd` — organizers
- `_quarto.yml` — site config / navbar / theme

## TODO

- Add conference date once confirmed.
- Replace listserv placeholder link with real sign-up.
- Add discussant assignments (summer).
