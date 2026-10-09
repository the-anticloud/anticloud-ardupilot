# Ethics — ARDUPILOT

**Project:** ARDUPILOT  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/ArduPilot/ardupilot  
**Pinned commit:** `cafe67457776027a1bad6e165c409828c1a851e5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `40a58be2b3a01f3e385b5fa4705704e5c5b897f7952ea9c49a7447dc1defea9f`  
**Date:** October 2026

## Position

ARDUPILOT is packaged for offline deployment with a verifiable audit trail. The
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
