# 03. PC12 cell culture and NGF-driven neuronal differentiation

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Not yet validated in the Zosen Lab. |
| Source papers | Zosen and Glazova 2016, [doi:10.1007/s11055-016-0277-y](https://doi.org/10.1007/s11055-016-0277-y). Zosen et al. 2018, [doi:10.1016/j.neulet.2018.06.056](https://doi.org/10.1016/j.neulet.2018.06.056). Yadav et al. 2021, [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007) |
| Role of the Zosen Lab PI | First author of the 2016 and 2018 papers. In the 2021 paper, differentiated the PC12 neurons, analysed that arm and edited the manuscript. |
| Licence | CC BY 4.0 |

## Purpose

Grow rat PC12 pheochromocytoma cells and differentiate them into neuron-like cells with nerve growth factor (NGF). The three papers use three variants, which this protocol lays out side by side.

## Before you start

- Read chapters 7 and 8 of the [lab handbook](https://github.com/deniszosen/lab-handbook). Authenticate the line and test for mycoplasma on the lab's schedule. None of the three papers states a schedule.
- U0126 and nutlin-3 are bioactive compounds. Read their safety data sheets. Make stock solutions as in protocol 13.

## Materials

| Item | Variant A: 2016 | Variant B: 2018 | Variant C: 2021 |
|---|---|---|---|
| Medium | DMEM (Sigma), 10% horse serum, 5% fetal calf serum | DMEM, 10% horse serum, 5% FBS, penicillin-streptomycin (all Sigma) | DMEM (Lonza), penicillin-streptomycin, sodium pyruvate, 5% horse serum, 10% FBS (BioWest) |
| Coating | Collagen type IV (Sigma) | Rat-tail collagen (Roche 11 179 179 001) | Collagen bio-coat BD Falcon 96-well plates (for the high-content assay) |
| NGF | Not mentioned in the Methods section | 50 ng/mL (Millipore 01-125) in DMEM with 1% horse serum, for 6 days | 50 ng/mL final, with 2% final horse serum, for 72 hours |
| Test compounds | Nutlin-3 (Tocris) and U0126 (Tocris) | U0126 10 µM (Tocris 1144) | PFOS and a defined POP mixture, DMSO solvent control 0.1% |
| Incubator | 37 °C, 5% CO2, 95% humidity | 37 °C, 5% CO2 (not otherwise stated) | 37 °C, 5% CO2 |

## Procedure

### Variant A: p53 and MEK pharmacology (2016)

1. Grow PC12 cells in six-well plates coated with collagen IV (biochemistry) or on collagen IV-coated slides placed in Petri dishes (morphology). Change the medium every 2 days.
2. Four groups, each run in two repeats per series: control (5 µL DMSO), nutlin-3 (5 µM on day 4 and 2.5 µM on day 6), U0126 (10 µM on days 4, 6 and 8), and U0126 plus nutlin-3 at the same doses.
3. Add the compounds directly to the culture medium on those days.
4. Harvest on day 10. Lyse one set for western blotting (protocol 26). Fix the other in 4% formalin for morphology (protocol 16).
5. The Methods section of this paper does not mention NGF. Check your own records before you assume the cells were NGF-differentiated.

### Variant B: NGF differentiation and MEK inhibition (2018)

1. Grow PC12 cells on collagen-coated plates in growth medium. When confluence reaches about 50 to 60%, change to DMEM with 1% horse serum and 50 ng/mL NGF to start differentiation.
2. Keep the cells in NGF for 6 days.
3. On the next day, change to plain DMEM and add 10 µM U0126 for 1, 2 or 4 hours (n = 6 for each time point).
4. At each time point, collect the medium for the dopamine ELISA (protocol 28) and homogenise the cells for western blotting (protocol 26).

### Variant C: toxicity screening with NGF (2021)

1. Seed cells in 96-well plates (100 µL per well) or 35 mm dishes (1 mL per dish) in serum-free medium. Allow 4 to 6 hours for attachment and serum starvation.
2. Without removing the medium, add an equal volume of fresh medium containing horse serum (2% final), NGF (50 ng/mL final) and the test compounds or controls.
3. Incubate for a further 72 hours before the assay.
4. Use these seeding densities:
   - MTT and high-content imaging: 1 × 10^4 cells/cm². Run each with and without NGF.
   - Glutathione measurement (black 96-well plates): 1 × 10^4 cells/cm².
   - Luciferase reporter (35 mm dishes): 1.25 × 10^4 cells/cm², allowed to attach for 24 hours. Transfect on culture day 1 and expose on day 2 in serum-free or serum-free plus NGF medium. Measure after 48 hours.
   - Live neurite imaging: 0.8 × 10^4 cells/cm² with NGF and 1.6 × 10^4 cells/cm² without NGF. Plates are scanned every 60 minutes for 72 hours.
5. Include valinomycin (15 µM in the paper) as a positive control for mitochondrial toxicity in the MTT and high-content assays.

## Quality checks

- Look for neurite outgrowth under phase contrast, with and without NGF, before you start any exposure.
- Keep a solvent control (0.1% DMSO in variant C) in every plate, and an NGF-free control where the design needs it.

## Not stated in the papers: set and record these

- passage number range and passaging ratio
- thawing, freezing and expansion conditions before differentiation
- the coating density of collagen
- whether NGF was added in the 2016 study
- the culture-to-culture interval that defines an independent experiment (the 2021 paper reports 3 to 4 independent experiments with more than 4 replicates per group)

## Related protocols

08 coating, 13 compound exposure, 14 neurite imaging, 16 F-actin staining, 17 high-content health assay, 26 western blot, 28 dopamine ELISA, 29 luciferase assay, 33 MTT assay, 35 glutathione assay.
