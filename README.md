# Xayra website — staging files

Static website intended for Cloudflare Pages at xayra.org.

**Do not deploy this bundle without approving `privacy/index.html` and `terms/index.html`: both contain visible draft notices and provisional wording.** The privacy policy is a condensed draft, not the complete approved policy. These pages are not yet suitable as the app's definitive Google Play legal links.

Cloudflare Pages Git integration settings:
- Production branch: `main`
- Framework preset: `None`
- Build command: blank
- Build output directory: `/`

Folder layout: `index.html`, `styles.css`, `support/index.html`, `privacy/index.html`, `terms/index.html`.

Before deployment: replace legal drafts with approved versions, remove draft notices, set publication dates, verify any substantive marketing claims, then deploy to temporary `pages.dev` address before connecting xayra.org.

The website does not require changing MX, SPF, DKIM or DMARC DNS records used by Zoho Mail.
