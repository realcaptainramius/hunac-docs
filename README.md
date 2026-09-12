# hunac-docs

Shared public docs site for Hunac Enterprises apps — support and privacy
policy pages required for App Store Connect. Plain static HTML, no build
step, one page per app under its own folder:

- `/fleet-mate/` — Fleet Mate (VMT)
- `/verbos/` — verbOS

Add a new folder the same way for any future app.

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
