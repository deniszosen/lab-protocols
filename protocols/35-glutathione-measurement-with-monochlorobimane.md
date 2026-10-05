# 35. Total reduced glutathione with monochlorobimane

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a short published method that follows Sørvik et al. 2018. Not yet validated in the Zosen Lab. |
| Source paper | Yadav et al. 2021, [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007) |
| Role of the Zosen Lab PI | Contributing author. |
| Licence | CC BY 4.0 |

## Purpose

Measure total reduced glutathione (GSH) in live cells with monochlorobimane (mBCl), a probe that becomes fluorescent when it binds GSH, and correct for cell number with Hoechst 33342 in the same wells.

## Before you start

The paper prints "CGNs" in this section, but the study used PC12 cells. This is probably text carried over from the earlier method. Run the assay in the cell type of your own experiment, and verify the cell type with the authors if you cite it.

## Materials

- Monochlorobimane (Sigma-Aldrich).
- Black 96-well plates.
- Experimental buffer: 140 mM NaCl, 3.5 mM KCl, 15 mM Tris-HCl (pH 7.4), 5 mM glucose, 1.2 mM Na2HPO4 (pH 7.4), 2 mM CaCl2. Prepare it fresh.
- Hoechst 33342.
- Plate reader (CLARIOstar) with filters for mBCl and Hoechst.

## Procedure

1. Seed cells in black 96-well plates at 1 × 10^4 cells/cm² and expose them to the test compounds for 72 hours (protocol 13).
2. Remove the medium and add new medium containing mBCl at 40 µM. Incubate in the dark at 37 °C for 30 minutes.
3. Remove the medium. Wash the plate with the freshly prepared experimental buffer, then add 100 µL of buffer to each well.
4. Read mBCl fluorescence at 380 nm excitation (15 nm bandwidth) and 478 nm emission (21 nm bandwidth).
5. Replace the buffer with Hoechst 33342 (0.4 µg/mL) and incubate in the dark for 1 minute.
6. Read Hoechst at 350 nm excitation (22 nm bandwidth) and 461 nm emission (36 nm bandwidth).
7. Subtract the blank (no-cell) values from both readings. Divide the mBCl signal by the Hoechst signal to correct for cell number.

## Unit flags

The text layer of the paper prints "40 mM" mBCl and "0.4 mg/mL" Hoechst, with the same pattern of µ rendered as m seen elsewhere in this paper. The values above read them as 40 µM and 0.4 µg/mL. These are my reading, not what the paper prints. Verify the concentrations with the authors or in the original PDF before use.

## Not stated in the paper

- the blank definition and the instrument gain
- the volume of the medium containing mBCl
- the normalisation to the solvent control

## Related protocols

13 compound exposure, 17 high-content assay, 29 GCLC promoter reporter, 44 statistics.
