# 05_NIST_SP800_53 - APPTAINER

**Project:** APPTAINER (SUPERCOMPUTER)
**Upstream:** https://github.com/kaczmarj/apptainer-in-docker
**Pinned commit:** 977b4525506c...
**BENCH.json SHA3-256:** `262e567658dc1416caa9d3c2720bf3491d78c5deb20e26ddb0593c17c803cee5`

## Control set

This folder binds the 05_NIST_SP800_53 control set to measured evidence.
Each control maps to a check in the 16-check assurance suite; results
are recorded per-row in ISOLATED_LAB_RESULTS/03_Result_Register.md
with the pass condition, exact command, observed value, and the
SHA3-256 of that check’s own evidence file.

## Evidence

- Suite report: `BENCH.json` (SHA3-256 above)
- Per-check register: `ISOLATED_LAB_RESULTS/03_Result_Register.md`
- Evidence files: `ISOLATED_LAB_RESULTS/04_Evidence/`

No certification is claimed. Frameworks are reported against with
evidence on disk; certification is a roadmap item.

> Self-assessment only. No external audit has been performed. A SOC 2 / NIST independent audit is committed post-funding.
