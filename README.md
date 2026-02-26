# ops/ — Operational Red Team Content

**SENSITIVE: Contains competition strategy, payload library, and deployment materials.**

This directory contains materials that are specific to offensive use. Keep access restricted.

## Contents

| Directory | Description |
|-----------|-------------|
| `payloads/` | Payload library. `ccdc-library.ps1` (69 payloads, 13 categories). `MEME-PAYLOADS.md` (7 meme payloads, unvalidated). |
| `competition/` | CCDC competition package. Strategy, deployment guide, quick reference, and pre-generated payloads. |

## Quick Links

- **Payload library:** `ops/payloads/ccdc-library.ps1`
- **Meme payloads:** `ops/payloads/MEME-PAYLOADS.md`
- **Competition strategy:** `ops/competition/COMPETITION-STRATEGY.md`
- **Competition deployment guide:** `ops/competition/DEPLOYMENT-GUIDE.md`
- **Competition quick reference:** `ops/competition/QUICK-REFERENCE.md`
- **Bulk deploy script:** `ops/competition/generate-all-deployments.sh` (run from project root)

## Notes

- `competition/generate-all-deployments.sh` must be run from the **project root**, not from inside `ops/competition/`
- The competition package was generated against v2.3 — regenerate after VM validation of v2.4
- `payloads/MEME-PAYLOADS.md` payloads are **unvalidated** — test before competition use
