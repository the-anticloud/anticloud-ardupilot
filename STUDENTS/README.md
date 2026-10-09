# Students — ARDUPILOT

**Project:** ARDUPILOT  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/ArduPilot/ardupilot  
**Pinned commit:** `cafe67457776027a1bad6e165c409828c1a851e5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `40a58be2b3a01f3e385b5fa4705704e5c5b897f7952ea9c49a7447dc1defea9f`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `cafe67457776027a1bad6e165c409828c1a851e5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `40a58be2b3a01f3e385b5fa4705704e5c5b897f7952ea9c49a7447dc1defea9f`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
