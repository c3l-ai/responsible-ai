# responsible-ai

Landing site for the co-design workshop **Fairness & Trust in Educational AI**.

A single static page (`index.html`) — no build step. Pushed to `main`, it deploys
itself to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.

## Live URL

Once Pages is enabled, the site publishes at:

```
https://<owner>.github.io/responsible-ai/
```

## Deploy (one-time setup)

1. Create the repo and push this folder (see commands below).
2. In the repo on GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. That's it. The workflow runs on the next push and on every push to `main` thereafter.

## Editing

Everything lives in `index.html`. Three things are marked with `<!-- TODO -->` comments:

- the **registration link** (appears in three places),
- the **date & time** (currently "To be confirmed").

Edit, commit, push — the change is live in a minute or two.

## Custom domain (optional)

To serve from e.g. `responsibleai.c3l.ai`, add a `CNAME` file containing just that
hostname, point a DNS CNAME record at `<owner>.github.io`, then set the custom domain
under Settings → Pages.
