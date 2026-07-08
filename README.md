# Noblit Site

Public GitHub Pages source for Noblit's homepage, privacy policy, and support page, plus the direct download links for the signed macOS and Windows desktop builds.

This folder is copied to the separate public repository:

```text
ai-org-labs/noblit-site
```

Regenerate it from the app repo with:

```sh
npm run site:prepare   # copies site/ to ../noblit-site
```

## GitHub Pages settings (public repo)

- Source: GitHub Actions
- Workflow: `.github/workflows/pages.yml`

This site is static HTML and includes `.nojekyll`, so it does not depend on a Jekyll build.

Public paths:

- `/` — homepage
- `/privacy/`
- `/support/`

## Downloads

App builds are produced by the app repo's release GitHub Actions (macOS `.dmg`, Windows `.msi`) and attached to releases in `ai-org-labs/noblit-site`. While the public build is a prerelease self-signed preview, the site's download buttons link directly to the release tag instead of `releases/latest`.

Distribution states:

- Preview: self-signed Windows and unnotarized macOS artifacts. These must be marked as prerelease and may show platform security warnings.
- Public trusted: macOS Developer ID signed and notarized, plus trusted Windows code signing.

Keep the app source in the private app repository. Only public-facing static HTML belongs here.
