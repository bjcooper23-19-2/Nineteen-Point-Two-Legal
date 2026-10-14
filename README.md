# Nineteen Point Two Legal

Standalone, low-maintenance legal and procurement estate for Nineteen Point Two Ltd. Canonical routes are `/`, `/website-terms/`, `/privacy/`, `/cookies/`, `/data-processing-agreement/`, `/security/` and `/subprocessors/`.

There is no analytics, pixel, lead capture or product login dependency. Edit the relevant HTML document, update its version and date, run validation, and open a review. Keep shared company statements separate from product-specific WAIA or Outside Clarity processing. Preserve the broad commitment that Nineteen Point Two Ltd does not intentionally use Customer Data to train AI models.

Deploy with GitHub Pages using `CNAME`. DNS must point `legal.nineteenpointtwo.com` to the repository’s Pages target; no DNS change is made here. Follow `docs/legal-estate-migration.md` before retiring legacy URLs.

Validation: `npx prettier --check .`; `npx html-validate '*/index.html' 'index.html'`; `git diff --check`; `xmllint --noout sitemap.xml`; check internal links and sitemap routes; search for stale `waia.nineteenpointtwo.com`, unsupported supplier claims and legacy CTAs; inspect at 390px and 1440px with keyboard focus checks.

The initial migration was checked against the live shared documents retrieved 9 September 2026 and `WAIA-Marketing-Site/docs/legal-procurement-review.md`. The proposed WAIA reconciliation, exact amendments and unresolved approval gates are recorded in `docs/waia-final-reconciliation-review.md`. Draft wording must not be treated as an operative customer commitment before legal and factual sign-off.
