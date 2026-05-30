# cirelay.com

Marketing site for Cirelay Ventures. Static HTML/CSS, no build step. Served via GitHub Pages with `cirelay.com` as the custom domain.

## Local preview

Just open `index.html` in any browser. No build or dependencies.

## Main Pages

- `index.html` - Cirelay Ventures overview.
- `marketplace-account-management.html` - broader Amazon/Walmart account-management service page.
- `marketplace-ops-audit.html` - fixed-scope pilot offer for the first paid service.
- `marketplace-audit-sample.html` - public sample audit using Cirelay-owned storefront assets.
- `audit-sample-shop-cirelay.png` - screenshot asset used by the sample audit page.
- `privacy.html` - privacy and data handling practices.

## Deployment

GitHub Pages serves from the `main` branch root. Pushes auto-deploy. The `CNAME` file maps the Pages site to `cirelay.com` — make sure DNS at the registrar points there:

- Apex `cirelay.com` → A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- (Or use `www.cirelay.com` CNAME → `cirelay-ventures.github.io`)
