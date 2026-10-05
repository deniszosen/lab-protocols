# 32. cDNA synthesis and quantitative PCR for mRNA and miRNA

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a short published method. The primer sequences are in Table 1 of the paper and are not reproduced here. Not yet validated in the Zosen Lab. |
| Source paper | Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056). It cites Nolan et al. 2006 for the qPCR protocol and Livak and Schmittgen 2001 for the analysis. |
| Role of the Zosen Lab PI | Second author. |
| Licence | CC BY 4.0 |

## Purpose

Validate miRNA changes found by sequencing (protocol 31) by reverse transcription and qPCR in chicken tissue and human cells.

## Materials

- RNA from protocol 30, 250 to 1000 ng per reaction.
- Reverse transcription kit (Thermo 4387406).
- A qPCR instrument.
- Primers: miR-363 (the human counterpart of miR-92), U6 and β-actin for human samples, and miR-92, GAPDH and others for Gallus gallus. The exact primer sequences are in Table 1 of the paper.

## Procedure

1. Reverse transcribe 250 to 1000 ng of RNA into cDNA.
2. Run the qPCR on the published protocol of Nolan et al. 2006, with these conditions: pre-incubation at 95 °C for 5 minutes, then **45 cycles** of denaturation at 95 °C for 5 seconds, annealing at 60 °C for 10 seconds and extension at 72 °C for 10 seconds.
3. Normalise gene expression to housekeeping genes with the 2^−ΔΔCt method (Livak and Schmittgen 2001).
4. Normalise experimental values to the average control value before statistics (protocol 44).

## Not stated in the paper

- the reverse transcription conditions and the primer concentrations
- the qPCR chemistry (SYBR green or probe) and the instrument
- the melt curve and the no-template and no-RT controls
- which housekeeping gene was used for which sample

## Related protocols

30 RNA isolation, 31 small RNA sequencing, 44 statistics.
