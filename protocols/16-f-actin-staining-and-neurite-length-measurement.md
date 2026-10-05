# 16. F-actin (phalloidin) staining and neurite length measurement in ImageJ

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a short published method. Not yet validated in the Zosen Lab. |
| Source paper | Zosen and Glazova 2016, [doi:10.1007/s11055-016-0277-y](https://doi.org/10.1007/s11055-016-0277-y) |
| Role of the Zosen Lab PI | First author. |
| Licence | CC BY 4.0 |

## Purpose

Stain the actin cytoskeleton and nuclei of PC12 cells grown on slides, and measure neurite length from the fluorescence images.

## Materials

- PC12 cells on collagen IV-coated slides placed in Petri dishes (protocol 03, variant A).
- 4% formalin in PBS. PBS.
- Phalloidin-Atto 565 (Sigma), 20 pM as printed in the paper (the text layer may have lost a prefix: confirm against the typeset PDF, since 20 pM is very low for a phalloidin conjugate).
- DAPI (Sigma), 500 ng/mL.
- Mowiol ("Moviol") mounting medium.
- Fluorescence microscope and ImageJ (non-commercial).

## Procedure

1. Fix the cells on the slides in 4% formalin in PBS for 30 minutes at +4 °C.
2. Wash with PBS.
3. Incubate in the phalloidin-Atto 565 solution for 1 hour.
4. Stain the nuclei with DAPI at 500 ng/mL for 5 minutes.
5. Wash with PBS and mount the slides in Mowiol.
6. Examine under a fluorescence microscope.
7. Measure neurite length in ImageJ.
8. Analyse statistically. The paper used Student's t-test, with n as the number of cells in the group, and p < 0.05 as the significance level.

## Not stated in the paper

- the permeabilisation step, if any (phalloidin normally needs permeabilised cells)
- the microscope, objective and exposure settings
- how a neurite was defined and how cells were chosen for measurement
- the number of cells measured per group

## Related protocols

03 PC12 culture, 14 automated neurite analysis.
