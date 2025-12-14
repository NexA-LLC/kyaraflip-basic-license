# KyaraFlip Fundamental License (KFL)

This repository is the canonical, versioned source for the **KyaraFlip Fundamental License (KFL)**.  
Japanese README: `README.md`

- **Stable (immutable)**: `v0.9r/`
- **Draft (may change)**: `v1.0-draft/`

## Canonical language (JA / EN)

- `v*/license.ja.md` is the canonical, authoritative text.
- `v*/license.en.md` is provided for convenience only.
- If there is any inconsistency, the Japanese text prevails.

## Repository License vs. License Texts

- Repository contents (tooling, schemas, and other non-license source files) are licensed under **Apache-2.0**. See `LICENSE`.
- License texts under `v*/` are contractual documents. The repository Apache-2.0 license does **not** apply to the license texts themselves.

## Versioning policy

- Once a version is released/tagged, treat its directory as **immutable** (no edits; roll forward only).
- Draft work must stay under `v1.0-draft/` until it is promoted to a new version directory.

## Directory layout

```
v0.9r/                 # Immutable release
  license.ja.md
  license.en.md
  manifest.json
v1.0-draft/            # Draft (not effective)
  license.ja.md
  license.en.md
  rrr-spec.md
  metadata-schema.json
  revshare-schemas/
    kf-1.0-default.json
```

## Referencing from other repositories

Prefer referencing by **tag** or **commit hash** (instead of git submodules):

- Example: `KFL v0.9r (commit <sha>)`
- Canonical URL: https://github.com/NexA-LLC/kyaraflip-basic-license

