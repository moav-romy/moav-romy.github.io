# Romy Moav

A concise personal landing page for Romy Moav, writer and cybersecurity practitioner working at the intersection of business, product, and AI.

## Local preview

Because the site is static, serve the repository root with any local HTTP server:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Deployment

The repository deploys automatically to GitHub Pages whenever `main` is updated. The workflow lives in `.github/workflows/pages.yml` and requires no build step. The intended custom domain is `romy-moav.com`.

To finish custom-domain setup, configure DNS at the domain provider:

- `A` records for `@` to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`
- A `CNAME` record for `www` to `moav-romy.github.io`
