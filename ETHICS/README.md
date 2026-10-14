# Ethics — MEDUSA_PRIOR_DOCS

**Project:** MEDUSA_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/medusajs/medusa  
**Pinned commit:** `f274f4e0739e487733354f329f2f29ad673a8647`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8bfd6042f75bc8bfe483c8390b41b157323ada0c50b51a41c77f00759ef3d121`  
**Date:** October 2026

## Position

MEDUSA_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
