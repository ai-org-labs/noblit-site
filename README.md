# Noblit Site

This folder contains the public GitHub Pages source for Noblit's first App Store submission.

It is designed to be copied to a separate public repository, for example:

```text
noblit-site
```

Recommended GitHub Pages settings for the public site repository:

- Source: GitHub Actions
- Workflow: `.github/workflows/pages.yml`

This site is static HTML and includes `.nojekyll`, so it does not depend on a GitHub Pages Jekyll build.

Expected public paths:

- `/privacy/`
- `/support/`

Only public-facing policy and support content should be copied to the public site repository. Do not copy the private app source or internal release docs unless intentionally publishing them.
