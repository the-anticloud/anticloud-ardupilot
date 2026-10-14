# Educators — ARDUPILOT

**Project:** ARDUPILOT  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/ArduPilot/ardupilot  
**Pinned commit:** `cafe67457776027a1bad6e165c409828c1a851e5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `40a58be2b3a01f3e385b5fa4705704e5c5b897f7952ea9c49a7447dc1defea9f`  
**Date:** October 2026

## Teaching with ARDUPILOT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `40a58be2b3a01f3e385b5fa4705704e5c5b897f7952ea9c49a7447dc1defea9f` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
