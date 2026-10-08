# PointsPoints — GitHub Pages website

A lightweight, responsive multi-page static website for **PointsPoints**, a planned privacy-first credit-card rewards companion. Built using plain HTML, CSS, and JavaScript; no npm, build pipeline, runtime service, or dependencies are required. Fonts are loaded from Google Fonts with system-font fallback.

## Pages

- `index.html` — Homepage / product preview
- `features.html` — Feature overview
- `faq.html` — Common questions
- `privacy.html` — **DRAFT** privacy policy (must be reviewed before public launch)
- `terms.html` — **DRAFT** terms (must be reviewed before public launch)
- `support.html` — Contact page
- `404.html` — Not-found page
- `assets/styles.css`, `assets/site.js`, `assets/favicon.svg` — Shared assets

## Publish with GitHub Pages

1. Create a new **public** GitHub repo, ideally named `pointspoints` (or `YOUR-USERNAME.github.io` for a root-domain site).
2. Upload the contents of this folder to the repo root (including `.github/`).
3. Go to **Settings → Pages → Build and deployment** and choose **Source: GitHub Actions**.
4. Push to `main`. The included workflow deploys the website.
5. The URL will be `https://YOUR-USERNAME.github.io/pointspoints/` for a project repo, or `https://YOUR-USERNAME.github.io/` for a special user site.

To preview locally: `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Required edits before public release

- **Contact**: In `support.html`, replace `hello@example.com` with a real email address.
- **Privacy + terms**: These are **draft placeholders**, not validated policies. Have them reviewed and updated to reflect actual operations and your company legal entity.
- **Product claims**: Product is presented as **in development**. Update feature availability and App Store links when appropriate.
- **Branding**: Replace illustrative app preview with real app screenshots once released. Verify rights before adding issuer logos.
- **Affiliates**: Add clear affiliate disclosures wherever qualifying partner links appear; comply with partner terms.
- **Domain**: In Settings → Pages, enter your custom domain. GitHub will advise the required DNS records. Optionally add a `CNAME` file containing only the domain, e.g. `www.pointspoints.com`, once you own and configure it. **Do not add a domain you have not verified.**

## Design notes

No bank connections, manual transaction ledger, or paid core features are promised. Examples in the mockup are fictional and do not represent a specific credit card offer. The site uses relative links so it works under a GitHub project path as well as a custom root domain.

## License

All rights reserved until the repository owner selects a license. Do not assume third-party rights to the PointsPoints name or brand.
