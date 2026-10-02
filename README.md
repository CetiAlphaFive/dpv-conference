# Democracy and Political Violence Collaborative — Website

Quarto website for the Democracy and Political Violence Collaborative.

## Local development

```bash
quarto preview   # live reload at http://localhost:port
quarto render    # build to _site/
```

## Deployment

Pushing to `main` triggers a GitHub Action that renders the site and publishes it to the
`gh-pages` branch. Live at: https://dpvconf.com

## Structure

- `index.qmd` — landing page for the Collaborative (mission, upcoming, past events, listserv)
- `about.qmd` — organizers and contact
- `mpsa2027/index.qmd` — MPSA 2027 mini-conference call for submissions
- `apsa2026/` — APSA 2026 pre-conference (Harvard) archive
    - `index.qmd` — overview, group photo, poster awards, sponsors
    - `schedule.qmd`, `panels.qmd`, `posters.qmd` — program (old root URLs redirect here via `aliases`)
- `_quarto.yml` — site config / sidebar / theme
