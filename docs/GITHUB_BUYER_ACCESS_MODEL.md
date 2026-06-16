# Zebepay GitHub Buyer Access Model

## Repository Separation

```text
zebepay-preview
  Public buyer preview, screenshots, product proof, deal request, pricing
  summary, compliance boundary, and safe preview package manifest.

zebepay
  Private full source-code delivery, buyer ZIP, SHA256 checksum, release audit,
  setup/deployment docs, support docs, and implementation handoff.
```

## Public Preview Access

The public preview repository may be viewed by prospective buyers. It must not
contain full source code, backend source, app source, shared package source,
database migrations, buyer ZIPs, private release audits, commercial decision
records, env files, logs, tokens, secrets, private emails, internal paths, or
machine-specific files.

## Private Source Access Gate

Do not give full Zebepay source access until all conditions are true:

- Buyer is approved.
- Payment is confirmed.
- License terms are accepted.
- Refund policy is accepted.
- Support scope is accepted.
- Buyer GitHub username or organization is confirmed.
- Delivery event is recorded.

## Access Method

Approved buyers should be added to the private `zebepay` repository only for the
approved review or delivery window. Access may be read-only for evaluation or
expanded according to the signed commercial terms.

## Revocation

Access should be removed when the review period ends, when a deal is declined,
after breach of confidentiality, or when MD directs revocation.
