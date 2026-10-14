# Ethics — PYGEOSTAT

**Project:** PYGEOSTAT  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `8064401382a4e5f739682e31a647904e92c2cc4a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `45acf2c6a881dc1e9f4f79ee16a349887cabc34ff6ff214043ba68256e4c3cf8`  
**Date:** October 2026

## Position

PYGEOSTAT is packaged for offline deployment with a verifiable audit trail. The
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
