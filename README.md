# Demibao GitHub Pages Site

This directory contains a minimal static release site for `脱密宝`.

## File Structure

```text
docs/github-pages/
  index.html
  styles.css
  README.md
  privacy/
    index.html
  support/
    index.html
  faq/
    index.html
```

## Deployment Options

### Option 1: Publish from a dedicated public GitHub Pages repository

Recommended steps:

1. Create a new public repository such as `demibao-pages`.
2. Copy the contents of `docs/github-pages/` into the root of that repository.
3. Push to the `main` branch.
4. In GitHub repository settings, open `Pages`.
5. Set the source to:
   - `Deploy from a branch`
   - `main`
   - `/ (root)`
6. Wait for GitHub Pages to publish the site.

Expected project-site URL:

- `https://<owner>.github.io/demibao-pages/`

If you want the shorter URL structure used in the planning document, rename the repository to `demibao`.

Expected URL structure:

- Home: `https://<owner>.github.io/demibao/`
- Privacy Policy: `https://<owner>.github.io/demibao/privacy/`
- Support: `https://<owner>.github.io/demibao/support/`
- FAQ: `https://<owner>.github.io/demibao/faq/`

### Option 2: Publish from the `docs/` directory of a public repository

If you place this folder inside a separate public repository, you can also:

1. Move these files to the repository `docs/` directory root, or keep them in the root and deploy from `/`.
2. In `Pages`, choose:
   - `Deploy from a branch`
   - `main`
   - `/docs`

## Before Publishing

Replace the placeholder fields in the HTML files:

- support email
- privacy contact email
- developer / operator name
- effective date

## App Store Connect Mapping

- `Privacy Policy URL` -> `/privacy/`
- `Support URL` -> `/support/`
- `Marketing URL` (optional) -> `/`
