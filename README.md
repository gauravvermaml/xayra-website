# Xayra website

Source for https://xayra.org: a static site with no build step.

## Deployment

Cloudflare Pages deploys this repository's `main` branch to xayra.org
automatically. **A push or merge to `main` publishes the site.** Make changes
on a branch, open a pull request, and merge only after the owner approves.

Cloudflare Pages settings:
- Production branch: `main`
- Framework preset: `None`
- Build command: blank
- Build output directory: `/`

After a merge, check that the Cloudflare Pages deployment succeeded and read
the live pages; a commit on `main` alone doesn't prove the site changed.
`styles.css` is referenced with a version query (`/styles.css?v=N`); bump it
when the stylesheet changes so browsers fetch the new file.

## Pages

`index.html` (home), `support/`, `privacy/`, `terms/`, `data-deletion/`,
`styles.css`, `assets/`.

## Legal pages

`privacy/`, `terms/` and `data-deletion/` are the published legal pages;
https://xayra.org/privacy/ is Xayra's authoritative Privacy Policy. Change
their wording only with the owner's approval of the exact text, and update
the "Last updated" date when the substance changes.

The site doesn't require changing the MX, SPF, DKIM or DMARC records used by
Zoho Mail.
