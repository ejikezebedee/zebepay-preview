# Zebepay Preview Package Manifest

## Purpose

This repository is the public buyer preview for Zebepay. It proves the product
positioning and commercial boundary without exposing the private source code.

## Included Files

- `README.md`
- `LICENSE.md`
- `docs/PRODUCT_OVERVIEW.md`
- `docs/CODE_PREVIEW.md`
- `docs/GITHUB_BUYER_ACCESS_MODEL.md`
- `sales/DEAL_REQUEST.md`
- `release/PREVIEW_PACKAGE.md`
- `assets/marketplace/zebepay-product-cover.png`
- `artifacts/screenshots/customer-dashboard.png`
- `artifacts/screenshots/admin-console.png`
- `.github/ISSUE_TEMPLATE/deal-request.yml`
- `.github/ISSUE_TEMPLATE/config.yml`

## Excluded From Public Preview

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

## Verification Gates

Before publishing or updating this preview, verify:

- No legacy product branding.
- No source-code leakage.
- No secrets, tokens, env files, private emails, internal paths, or
  machine-specific files.
- The full `zebepay` repository remains private.
- The public repository contains preview/proof material only.
