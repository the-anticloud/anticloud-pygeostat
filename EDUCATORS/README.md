# Educators — PYGEOSTAT

**Project:** PYGEOSTAT  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `8064401382a4e5f739682e31a647904e92c2cc4a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `45acf2c6a881dc1e9f4f79ee16a349887cabc34ff6ff214043ba68256e4c3cf8`  
**Date:** October 2026

## Teaching with PYGEOSTAT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `45acf2c6a881dc1e9f4f79ee16a349887cabc34ff6ff214043ba68256e4c3cf8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
