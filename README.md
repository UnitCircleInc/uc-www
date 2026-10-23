# Unit Circle website

Source for [www.unitcircle.ca](https://www.unitcircle.ca), built with
[Zensical](https://zensical.org). Configuration is in `zensical.toml`; the
"Sumi & Ai" brand lives in `docs/stylesheets/extra.css`, `docs/assets/` and
`overrides/`.

## Local preview

    uv sync
    uv run zensical serve      # http://localhost:8000

## Deploy

Push to `main`. The `Deploy site` GitHub Actions workflow builds the site and
publishes it to GitHub Pages (Settings → Pages → Source: GitHub Actions). The
custom domain is set in the repository's Pages settings.
