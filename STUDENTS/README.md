# Students — MEDUSA_PRIOR_DOCS

**Project:** MEDUSA_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/medusajs/medusa  
**Pinned commit:** `f274f4e0739e487733354f329f2f29ad673a8647`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8bfd6042f75bc8bfe483c8390b41b157323ada0c50b51a41c77f00759ef3d121`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f274f4e0739e487733354f329f2f29ad673a8647`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `8bfd6042f75bc8bfe483c8390b41b157323ada0c50b51a41c77f00759ef3d121`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
