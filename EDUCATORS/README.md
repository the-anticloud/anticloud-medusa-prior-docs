# Educators — MEDUSA_PRIOR_DOCS

**Project:** MEDUSA_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/medusajs/medusa  
**Pinned commit:** `f274f4e0739e487733354f329f2f29ad673a8647`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8bfd6042f75bc8bfe483c8390b41b157323ada0c50b51a41c77f00759ef3d121`  
**Date:** October 2026

## Teaching with MEDUSA_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `8bfd6042f75bc8bfe483c8390b41b157323ada0c50b51a41c77f00759ef3d121` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
