# 38. Escitalopram, venlafaxine and metabolites in brain tissue by UPLC-MS/MS

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. The analysis was done at a hospital laboratory. Not yet validated in the Zosen Lab. |
| Source paper | Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) |
| Role of the Zosen Lab PI | Second author. The tissue was analysed by a hospital laboratory partner, and the method is "established in our laboratory" in the paper's words, meaning the partner's. |
| Licence | CC BY 4.0 |

## Purpose

Measure escitalopram, venlafaxine and their metabolites (desmethylcitalopram, O-desmethylvenlafaxine) in brain homogenates by liquid-liquid extraction and UPLC-MS/MS.

## Before you start

Treat this protocol as a record of what the partner did. Do not copy it to run in-house until an analytical chemist has reviewed it with you.

## Materials

- Homogenate: brain tissue weighed and homogenised 1:1 in Milli-Q water (autoclaved electric homogeniser with plastic pestle). Keep a 100 µL aliquot in a 5 mL plastic tube, refreeze in liquid nitrogen and store at −80 °C.
- Calibrators, quality controls and blanks in H2O or blood. Working solutions in MeOH:H2O (50:50), stored at 4 °C.
- Internal standards: citalopram-d6 (50 µL), venlafaxine-d6, O-desmethylvenlafaxine-d6.
- Borate buffer, pH 11, saturated solution. Ethyl acetate:heptane (80:20, v/v).
- Reconstitution: ice-cold mobile phase, acetonitrile/5 mM ammonium formate buffer pH 5 (25:75, v/v).
- Waters Acquity UPLC with a Xevo-TQS tandem mass spectrometer, electrospray ionisation, and MassLynx 4.2.
- BEH C18 column, 2.1 × 50 mm, 1.7 µm.

## Procedure

### Extraction

1. Thaw the 100 µL brain homogenate samples in cold water and add 50 µL H2O.
2. Add 50 µL of the internal standard (citalopram-d6, printed as 0.22 mmol/mL) and 75 µL of borate buffer to all samples except the blanks. Vortex briefly.
3. Add 1.2 mL ethyl acetate:heptane (80:20). Vortex, shake for 10 minutes, and centrifuge at 5250 × g and 4 °C for 10 minutes.
4. Move 750 µL of the supernatant to glass tubes. Evaporate to dryness under nitrogen at 40 °C for 10 to 20 minutes.
5. Reconstitute in 900 or 500 µL of ice-cold mobile phase and vortex for 2 minutes.
6. Move 300 µL of the supernatant to autosampler vials.

### Chromatography

- Mobile phase A: 5 mM ammonium formate buffer, pH 10.2. Mobile phase B: acetonitrile.
- Flow 0.5 mL/min. Column temperature 60 °C. Injection volume 3 µL. Total run time 8 minutes.
- Gradient (% B): 0 to 0.5 min, 10%. 0.5 to 0.51 min, 10 to 40%. 0.51 to 3.50 min, 40 to 73%. 3.50 to 5.50 min, 73 to 90%. 5.50 to 5.51 min, 90 to 98%. 5.51 to 7.00 min, 98%. 7.00 to 7.01 min, 98 to 10%. 7.01 to 8.00 min, 10%. The paper prints the segment boundaries in a compressed form, and the reading above follows the sequence of steps.

### Mass spectrometry

Positive ionisation, multiple reaction monitoring. Capillary 1 kV, source 150 °C, desolvation gas 600 °C, cone gas 150 L/h, desolvation gas 1000 L/h.

| Analyte | Quantifier | Qualifier |
|---|---|---|
| Venlafaxine | 278.2 > 260.0 | 278.2 > 121.0 |
| O-desmethylvenlafaxine | 264.2 > 58.01 | 264.2 > 107.0 |
| Escitalopram | 325.1 > 262.0 | 325.1 > 234.0 |
| Desmethylescitalopram | 311.1 > 262.0 | 311.1 > 234.0 |
| Citalopram-d6 (internal standard) | 325.1 > 262.0 | |
| Venlafaxine-d6 | 284.2 > 260 | |
| O-desmethylvenlafaxine-d6 | 270.2 > 64.01 | |

Calibration curves were linear with residuals within ±20%.

## Unit and value flags

- The paper prints calibrators of 0.05 to 3 nM and an internal standard of 0.22 mmol/mL. Both look like unit slips, since the measured brain concentrations are in the hundreds of nM. Verify with the laboratory.
- The injected venlafaxine stock is 1.27 mM in the Methods and 1.44 mM in one figure legend. Check which was used.

## Not stated in the paper

- the number of QC levels and the acceptance criteria
- the limit of quantification

## Related protocols

10 in-ovo exposure, 11 sample collection, 39 brain pharmacokinetics.
