# 17. High-content assay of nuclear and mitochondrial health in PC12 cells

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. Units printed in the paper's text layer need checking (see below). Not yet validated in the Zosen Lab. |
| Source paper | Yadav et al. 2021, [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007). The method follows Shannon et al. 2017 and Wilson et al. 2016, cited in the paper. |
| Role of the Zosen Lab PI | Contributing author. Differentiated the PC12 neurons and analysed that arm. |
| Licence | CC BY 4.0 |

## Purpose

Measure cell number, nuclear morphology and mitochondrial health in individual cells by automated imaging after a 72-hour exposure.

## Before you start

- This assay uses formalin (a hazardous fixative) and DMSO. Use a fume hood where the risk assessment asks for one.
- **Check units.** The paper's text layer prints "mM" where µM is clearly meant for the live-cell stain and for Hoechst 33342. Verify against the typeset PDF.

## Materials

| Item | Details as stated |
|---|---|
| Kit | Cellomics HCS reagent series, multiparameter cytotoxicity assay, used according to the manufacturer's instructions |
| Plates | Collagen bio-coat BD Falcon 96-well flat-bottomed microtitre plates (BD Biosciences) |
| Mitochondrial dye | MitoTracker Red CMXRos (Thermo Scientific). Dissolve in 117 µL anhydrous DMSO to make a 1 mM stock. |
| Nuclear dye | Hoechst 33342 (Thermo Scientific) |
| Fixative | 10% formalin |
| Positive control | Valinomycin (15 µM), which dissipates the mitochondrial membrane potential |
| Instrument | CellInsight NXT High Content Screening Platform (Thermo Fisher Scientific) |

## Procedure

1. Seed PC12 cells into collagen-coated 96-well plates at 1 × 10^4 cells/cm². Expose them to the test compounds with and without NGF for 72 hours (protocol 03, variant C).
2. After 72 hours, add 50 µL of live-cell stain (final concentration 0.1 µM as read from the paper) to each well and incubate for 30 minutes at 37 °C, protected from light.
3. Remove the live-cell stain and fix the cells with 10% formalin for 20 minutes at room temperature. Wash with PBS.
4. Add Hoechst 33342 (final 1.6 µM as read from the paper) to each well and incubate for 10 minutes at room temperature. Wash with PBS.
5. Fill the wells with 200 µL PBS and seal the plate with a plate sealer.
6. Read on the CellInsight NXT with the 10× objective. Excitation and emission wavelengths: Hoechst 350/461 nm, MitoTracker 554/576 nm. Acquire **nine fields of view per well**.

## Readouts

| Readout | Dye | Meaning |
|---|---|---|
| Cell number (CN) | Hoechst | Number of nuclei |
| Nuclear intensity (NI) | Hoechst | Staining intensity of nuclei |
| Nuclear area (NA) | Hoechst | Size of nuclei |
| Mitochondrial membrane potential (MMP) | MitoTracker | Mitochondrial health |
| Mitochondrial mass (MM) | MitoTracker | Amount of mitochondria |

Express the data as a percentage of the solvent control (0.1% DMSO), with n = 3 to 4 independent experiments and more than 3 replicates per group, as in the paper. The paper compared each group with the solvent control with the same NGF condition.

## Not stated in the paper

- the instrument thresholds and the analysis algorithm settings
- the bioapplication used on the platform
- how fields with too few cells are handled

## Related protocols

03 PC12 culture, 13 compound exposure, 33 MTT assay, 35 glutathione assay.
