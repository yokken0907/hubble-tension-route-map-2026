# Inline Citation Style v1.6.2

## Purpose

This document defines how citations are inserted in the Markdown manuscript.

## Format

For this draft, citation placeholders use BibTeX keys in square brackets:

```text
Planck Collaboration. Planck 2018 results. VI. Cosmological parameters. Astronomy & Astrophysics 641, A6 (2020). arXiv:1807.06209.
Riess et al. A Comprehensive Measurement of the Local Value of the Hubble Constant with 1 km/s/Mpc Uncertainty from the Hubble Space Telescope and the SH0ES Team. Astrophysical Journal Letters 934, L7 (2022). arXiv:2112.04510.
DESI Collaboration. DESI DR2 Results II: Measurements of Baryon Acoustic Oscillations and Cosmological Constraints (2025). arXiv:2503.14738.
```

Multiple citations:

```text
Planck Collaboration. Planck 2018 results. VI. Cosmological parameters. Astronomy & Astrophysics 641, A6 (2020). arXiv:1807.06209.; Riess et al. A Comprehensive Measurement of the Local Value of the Hubble Constant with 1 km/s/Mpc Uncertainty from the Hubble Space Telescope and the SH0ES Team. Astrophysical Journal Letters 934, L7 (2022). arXiv:2112.04510.
```

## Reason

This format can be converted later to Pandoc/LaTeX citations while remaining readable in GitHub Markdown.

## Strict rule

Do not insert a citation key unless the corresponding entry exists in `references/references.bib`.

## Current status

```text
Citation key insertion: PASS for minimum anchor set
Complete citation density: superseded
Full literature coverage: superseded
Public-final release: superseded
```
