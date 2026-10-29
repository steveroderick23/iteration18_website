# Iteration 18 website

Static site for [iteration18.com](https://iteration18.com): company page and hosted legal documents for our apps.

## Pages

- `/` — company homepage
- `/privacy.html` — index of privacy documents
- `/apps/syntegra-rp/privacy.html` — Syntegra RP privacy policy (Play Store URL)

## Hosting

GitHub Pages deploys from `master` via `.github/workflows/static.yml`.

Until DNS is pointed at GitHub Pages, the site is also available at:

`https://steveroderick23.github.io/iteration18_website/`

To serve `iteration18.com` from this repo:

1. In the repo, enable Pages with **GitHub Actions** as the source.
2. At GoDaddy, replace the current parked/forwarding A records with GitHub Pages:

   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`

3. Keep `www` as a CNAME to `iteration18.com`, or point it at `steveroderick23.github.io`.
