# Zebepay Public Preview Packaging Report

Date: 2026-06-16

## Result

Zebepay public preview package is prepared as a buyer-safe preview only. It does
not contain the full private source code.

## Repository Model

- `zebepay-preview`: public buyer preview, screenshots, product proof, deal
  request, pricing summary, compliance boundary, and preview package manifest.
- `zebepay`: private full source-code delivery, buyer ZIP, SHA256 checksum,
  release audit, setup/deployment docs, support docs, and implementation
  handoff.

## Included Files

- `README.md`
- `LICENSE.md`
- `docs/PRODUCT_OVERVIEW.md`
- `docs/CODE_PREVIEW.md`
- `docs/GITHUB_BUYER_ACCESS_MODEL.md`
- `sales/DEAL_REQUEST.md`
- `release/PREVIEW_PACKAGE.md`
- `release/PREVIEW_PACKAGING_REPORT.md`
- `assets/marketplace/zebepay-product-cover.png`
- `artifacts/screenshots/customer-dashboard.png`
- `artifacts/screenshots/admin-console.png`
- `.github/ISSUE_TEMPLATE/deal-request.yml`
- `.github/ISSUE_TEMPLATE/config.yml`
- `.gitignore`

## Excluded From Preview

- Full customer app source.
- Full admin app source.
- Backend API source.
- Shared package source.
- Database migrations.
- Buyer ZIP.
- Private release audit.
- Commercial decision records.
- Env files.
- Logs.
- Tokens.
- Secrets.
- Private emails.
- Internal infrastructure paths.
- Machine-specific files.

## Verification

- Legacy branding scan: required to return no active legacy brand references.
- Source-code leakage scan: required to return no app/API/shared/db/source files.
- Secret and env scan: required to return no secret, env, log, private-email, or
  internal-path artifacts.
- Private source check: full `zebepay` repository must remain private.

## Access Gate

Full Zebepay source access remains blocked until buyer approval, payment
confirmation, license acceptance, refund-policy acceptance, support-scope
acceptance, confirmed buyer GitHub username or organization, and recorded
delivery event.
