# 34. DNAq: in-well DNA quantification for cell number and normalisation

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method that follows Ligasová and Koberna 2019. Not yet validated in the Zosen Lab. |
| Source paper | Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130) |
| Role of the Zosen Lab PI | Contributing author. |
| Licence | CC BY 4.0 |

## Purpose

Quantify the DNA in fixed cells in the well, as a viability readout that does not depend on mitochondrial activity (so it complements MTT, protocol 33), and as a normalisation factor for immunocytochemistry plate-reader data (protocol 15, variant B). DAPI is stained, washed, then eluted and read, so the signal comes from DNA in the well and not from cell morphology.

## Before you start

- DNAq runs on cells that have already been fixed and stained by ICC, or on fixed cells alone.
- The wash buffer contains copper sulfate. Dispose of it as copper-containing waste according to your institution's rules.

## Materials

- DAPI staining solution: 3 µM DAPI in 20 mM Tris-HCl with 150 mM NaCl, pH 7.
- 70% ethanol. PBS.
- Wash buffer: 2 mM CuSO4, 0.5 M NaCl, 20 mM citrate, 0.2% Tween, pH 5.
- Rinse buffer: 20 mM Tris-HCl, 150 mM NaCl, pH 7.
- Elution solution: 2% SDS in 20 mM Tris-HCl, pH 7.
- Freshly washed Corning 3603 96-well plates for the eluates.
- Plate reader with a DAPI filter (CLARIOstar Plus, 360-20 nm excitation and 460-30 nm emission).
- Orbital shaker or agitator.

## Procedure

1. After treatment and ICC, wash the cells with PBS.
2. Re-fix in 70% ethanol for 10 minutes at room temperature.
3. Air-dry the plate for 30 minutes.
4. Incubate with the DAPI staining solution for 30 minutes on an agitator at room temperature.
5. Protect from light from now on. Discard the staining solution.
6. Wash three times with the wash buffer, 2 minutes per wash.
7. Rinse with the rinse buffer.
8. Elute the stained DNA with the elution solution for 15 minutes on an agitator at room temperature.
9. Transfer the eluates to the clean Corning 3603 plate.
10. Read in the plate reader with the DAPI filter set.
11. Use the readout as a viability measure, and to normalise ICC data (for example, tubulin signal divided by DNAq signal of the same sample).

## Quality checks

- From the paper: use 12 wells per treatment for DNAq (the paper's replicate count).
- General practice, not from the paper: include wells without cells for background subtraction, and check linearity with a dilution series of a known cell number before the first experiment.

## Not stated in the paper

- the volumes of each solution per well
- the agitation speed
- the background correction and any standard curve

## Related protocols

15 ICC, 33 MTT, 44 statistics.
