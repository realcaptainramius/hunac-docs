# vmt-docs

Public docs site for the Fleet Mate app — support and privacy policy pages,
required for App Store Connect. Plain static HTML, no build step.

Deployed via Cloudflare Pages at **docs.hunacenterprises.com**.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploying

Connected to Cloudflare Pages via the GitHub integration — every push to
`main` deploys automatically. No build command; the output directory is
the repo root (`/`).
