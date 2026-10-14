# Students — PYGEOSTAT

**Project:** PYGEOSTAT  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `8064401382a4e5f739682e31a647904e92c2cc4a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `45acf2c6a881dc1e9f4f79ee16a349887cabc34ff6ff214043ba68256e4c3cf8`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8064401382a4e5f739682e31a647904e92c2cc4a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `45acf2c6a881dc1e9f4f79ee16a349887cabc34ff6ff214043ba68256e4c3cf8`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
