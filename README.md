# jpalmer37.github.io

Source for John Palmer's professional portfolio, built with Quarto and published
to GitHub Pages.

## Local development

```bash
quarto preview
```

Run a complete production render before publishing:

```bash
quarto check
quarto render
```

The GitHub Actions workflow publishes the rendered site to the `gh-pages`
branch whenever `main` changes. The published site is available at
<https://jpalmer37.github.io>.

## Content boundaries

Case studies distinguish solely authored systems from shared organizational
work. Private source code, endpoints, account identifiers, partner names, and
deployment configuration are intentionally excluded.
