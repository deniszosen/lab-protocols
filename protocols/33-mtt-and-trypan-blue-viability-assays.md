# 33. MTT viability assay and trypan blue exclusion

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Collected from four papers with three cell types. Not yet validated in the Zosen Lab. |
| Source papers | Yadav et al. 2021 (PC12), [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007). Labba et al. 2022 (CGNs, NT2N), [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130). Kaplan-Arabaci et al. 2025 (CGNs), [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) |
| Role of the Zosen Lab PI | Contributing author (2021, 2022). Second author (2025). |
| Licence | CC BY 4.0 |

## Purpose

Estimate cell viability from the mitochondrial reduction of MTT to formazan (a readout of reductive activity, not a direct count of cells), and check for cell death with trypan blue. Always pair MTT with a second readout, such as DNAq (protocol 34) or nuclear counts (protocol 17), because a compound can change MTT conversion without killing cells.

## Materials

- MTT (3-(4,5-dimethylthiazol-2-yl)-2,5-diphenyltetrazolium bromide). Sources in the papers: Sigma 5655 (2025), Thermo M6494 (2022), Sigma-Aldrich (2021).
- DMSO (Sigma 41639 in 2025). Clear flat-bottomed 96-well plates (Nunc).
- Positive controls: valinomycin (2021, mitochondrial dysfunction) or H2O2 (1 mM, 2025).
- Plate reader (Sunrise, Tecan, 2021) or CLARIOstar (BMG Labtech).
- Trypan blue 0.2% (Gibco 15250061).

## Procedure

### Variant A: PC12 cells, 72 hours (2021)

1. Seed cells at 1 × 10^4 cells/cm² in clear 96-well plates and expose them to the test compounds, with or without NGF, for 72 hours (protocol 13).
2. Discard the supernatant. Add MTT at 2 mg/mL in PBS, diluted 1:6 in assay medium.
3. Remove the supernatant after the incubation (the paper does not state the time). Add 200 µL DMSO per well to dissolve the formazan crystals.
4. Incubate at 37 °C for 10 minutes with agitation.
5. Read absorbance at 570 nm with a 630 nm reference filter.
6. Express viability as the percentage of absorbance relative to the solvent control.

### Variant B: chicken CGNs and NT2N cells, 24 to 72 hours (2022)

1. Seed and treat the cells (protocols 02 and 04). Incubate for 24, 48 and 72 hours.
2. **Replace the treatment medium** with fresh defined medium containing 0.5 µg/mL MTT. This excludes any chemical reduction of MTT by the test compound (acetaminophen in that study). Leave 3 wells per plate without MTT for background subtraction.
3. Incubate at 37 °C and 5% CO2 for 2 hours.
4. Replace the MTT solution with 100 µL DMSO per well and incubate 30 minutes at 37 °C.
5. Read in the plate reader. Average the blank wells and subtract that value from all sample wells.
6. Use six wells per treatment.

### Variant C: chicken CGNs, 72 hours (2025)

1. Plate CGNs in 96-well plates at 1.7 × 10^5 cells per well (as printed). After 24 hours, expose to escitalopram (1, 10, 100 µM) or venlafaxine (2, 20, 200 µM) for 72 hours. Use 1 mM H2O2 as the positive control.
2. Remove the medium and add MTT at 5 mg/mL (as printed). Incubate at 37 °C and 5% CO2 for 3 hours.
3. Remove the mixture and add 100 µL DMSO. Incubate for 10 minutes.
4. Read absorbance at 570 nm.

### Trypan blue (2025)

Add 0.2% trypan blue to the culture medium to estimate cell death. The paper reports the result qualitatively (no cell death at the tested concentrations). For a quantitative count, add the dye to a suspension at 1:1, count dye-positive and dye-negative cells in a counting chamber within a few minutes. This counting detail is general practice, not from the paper.

## Notes and pitfalls

- The 2022 paper prints "490/570 nm ex/em". An absorbance assay has no excitation or emission, so treat it as a printing error and use 570 nm with the reference filter, as in the other variants.
- The 5 mg/mL concentration and the 1.7 × 10^5 per well in variant C are quoted as printed. A 96-well plate holds about 3 × 10^4 to 1 × 10^5 cells, so verify the value with the authors.
- MTT measures reductive activity. Interpret it together with protocols 34 and 17.

## Not stated in the papers

- the MTT incubation time in variant A
- the plate format and seeding density for variant B

## Related protocols

04 CGNs, 13 compound exposure, 17 high-content assay, 34 DNAq, 44 statistics.
