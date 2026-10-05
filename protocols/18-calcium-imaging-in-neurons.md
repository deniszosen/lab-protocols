# 18. Calcium imaging in differentiated neurons: Cal-520 live imaging and Fura-2 plate reader

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. Not yet validated in the Zosen Lab. |
| Source paper | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571) |
| Role of the Zosen Lab PI | First author. |
| Licence | CC BY 4.0 |

## Purpose

Measure spontaneous cytosolic calcium transients in single SH-SY5Y-derived neurons (Cal-520, live imaging), and measure the cytosolic calcium level of whole wells after a drug (Fura-2, plate reader).

## Before you start

Neurons must be differentiated and plated as in protocol 01. Calcium dyes are applied to live cells: record the time of every step.

## A. Spontaneous calcium transients with Cal-520

### Materials

- Cal-520 AM (Abcam ab171868), 1 µM in artificial cerebrospinal fluid (ACSF: in mM, 150 NaCl, 5 KCl, 1 MgSO4, 2 CaCl2, 10 glucose, 10 HEPES; pH 7.4; 300 to 310 mOsm/L).
- Upright microscope (Zeiss Axioskop FS) with a 40×/1.0 DIC W Plan-Apochromat objective (421462-99-00) and an Andor iXon Ultra 897 camera.
- WinFluor software.

### Procedure

1. Use neurons on 12 mm coverslips, plated on DIV 17 (protocol 01). Image on DIV 21.
2. Load the cells with 1 µM Cal-520 AM in ACSF for 30 minutes at 37 °C.
3. Transfer the coverslip to the recording chamber with standard ACSF.
4. Record time series at 10 Hz (512 × 512 pixels) for 5 minutes.
5. Analyse the traces in WinFluor to derive parameters of the calcium signals. Normalise each fluorescence trace to its initial intensity (ΔF/F0).

## B. Cytosolic calcium by Fura-2 on a plate reader

### Materials

- Black 96-well plates with a glass bottom (Corning 3340 or 3603).
- Fura-2/AM (Santa Cruz 108964-32-5), 4 µM.
- Normal buffer, in mM: 140 NaCl, 3.5 KCl, 15 Tris-HCl pH 7, 1.2 Na2HPO4 × NaH2PO4 pH 7.4, 5 glucose, 2 CaCl2, in ddH2O.
- 1 mM MgSO4 in Normal buffer for de-esterification.
- Controls: NMDA (Sigma M3262), glycine (Sigma G8790) and the non-competitive NMDA receptor antagonist (+)-MK-801 hydrogen maleate (Sigma M107).
- CLARIOstar microplate reader (BMG Labtech).

### Procedure

1. Plate differentiating neurons at 2 × 10^4 cells per well (protocol 01).
2. On DIV 21, load with 4 µM Fura-2/AM in 100 µL of culture medium per well for 30 minutes at 37 °C and 5% CO2.
3. Perform all later washes and drug exposures in Normal buffer.
4. De-esterify with 1 mM MgSO4 in Normal buffer for 10 minutes and wash twice.
5. Measure the baseline.
6. Replace the wash buffer with the test compounds in Normal buffer and measure [Ca2+]i **120 minutes** after the treatment.
7. Read the ratiometric signal F340/F380 (excitation 340 nm for Ca2+-bound and 380 nm for Ca2+-unbound, emission 510 nm).
8. Subtract the average background autofluorescence of wells with cells without Fura-2/AM from both excitation channels before calculating the ratio.
9. Run NMDA with glycine, with and without MK-801, as control experiments.

## Not stated in the paper

- the number of cells analysed per coverslip and the criteria for a calcium transient
- the exact times for plate-reader readings other than the 120-minute point
- the baseline reading time

## Related protocols

01 SH-SY5Y neurons, 13 compound exposure, 24 patch clamp (the same coverslips were used for patch clamp and Cal-520 imaging).
