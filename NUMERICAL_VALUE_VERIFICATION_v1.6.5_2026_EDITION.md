# Numerical Value Verification v1.6.5 - 2026 Edition

## Verified numerical anchors used in the handbook

| Value | Use | Source anchor | Status |
|---|---|---|---|
| H0 = 67.4 +/- 0.5 km/s/Mpc | Planck base-Lambda-CDM inferred H0 | Planck2018Parameters | PASS |
| H0 = 73.04 +/- 1.04 km/s/Mpc | SH0ES local distance ladder | Riess2022SH0ES | PASS |
| more than 14 million galaxies and quasars | DESI DR2 BAO sample scale | DESI2025DR2BAO | PASS |
| three years of operation | DESI DR2 basis | DESI2025DR2BAO | PASS |
| H0 = 67.80 +/- 2.17(stat) +/- 1.64(sys) km/s/Mpc | Lee/CCHP JAGB applied in CCHP overview | Lee2024JAGB | PASS |
| HST-JWST mean Cepheid distance difference -0.01 +/- 0.03 mag | Riess JWST Cepheid-crowding test | Riess2024JWSTCepheids | PASS |
| -3e-15 to +7e-16 | GW/EM speed-difference constraint from GW170817/GRB170817A | Abbott2017GW170817Speed | PASS |

## Rule

No numerical value should be added to reader-facing text unless it is tied to a named source anchor and checked against the current `references/references.bib` metadata.

## v1.6.5 CCHP/JWST update

A previous CCHP status row was removed from the current public ledger because it reflected an earlier status version and is not used as a public reader-PDF claim in this release.

Current ledgered CCHP v3 values are recorded only as source-status context, not as a final adjudication of the Hubble tension:

| Quantity | Value | Context | Source key | Status |
|---|---|---|---|---|
| H0 | 70.39 +/- 1.22(stat) +/- 1.33(sys) +/- 0.70(sigma_SN) km/s/Mpc | CCHP current best/highest-precision TRGB-based estimate using HST+JWST data and 24 SN Ia calibrators; not a three-method consensus closure claim | Freedman2025CCHPStatusV3 | PASS |
| H0 | 68.81 +/- 1.79(stat) +/- 1.32(sys) km/s/Mpc | CCHP JWST-only TRGB route tied to SNe Ia | Freedman2025CCHPStatusV3 | PASS |
| H0 | 67.80 +/- 2.17(stat) +/- 1.64(sys) km/s/Mpc | CCHP JWST-only JAGB route tied to SNe Ia | Freedman2025CCHPStatusV3 | PASS |

Reader-facing rule:
Do not present these values as resolving the Hubble tension. They are retained as route-map context for comparing distance-indicator branches.
