# 27. Western blot with infrared fluorescence detection (LI-COR Odyssey)

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a short published method. Not yet validated in the Zosen Lab. |
| Source paper | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571) |
| Role of the Zosen Lab PI | First author. |
| Licence | CC BY 4.0 |

## Purpose

Quantify neuronal and synaptic proteins in SH-SY5Y cells with fluorescent secondary antibodies, so that several targets and the loading control can be read on the same membrane.

## Materials

- SH-SY5Y cells in 6-well plates (protocol 01).
- RIPA buffer containing three protease inhibitors (leupeptin 5 µg/µL, pepstatin A 1 µg/µL, PMSF 300 µM) and the phosphatase inhibitor Na3VO4 (300 µM).
- Pierce BCA Protein Assay Kit (23225).
- Laemmli buffer with 5% mercaptoethanol.
- SDS-PAGE gels (Bio-Rad 4551095) and the Bio-Rad Mini-PROTEAN electrophoresis system.
- Primary antibodies against SYP, PSD-95, MAP2 and TUBB3, as listed in protocol 15. β-ACTIN (1:5000, Sigma A5346) as the loading control.
- Odyssey secondary antibodies goat anti-rabbit (GAR) 800 and 680, and goat anti-mouse (GAM) 680, at 1:10000 (LI-COR).
- Odyssey CLx Infrared Imaging System.

## Procedure

1. Wash the cells with 1× PBS and lyse them in RIPA buffer with the inhibitors.
2. Measure the protein concentration with the BCA kit.
3. Mix the samples with Laemmli buffer with 5% mercaptoethanol and denature at 95 °C for 5 minutes.
4. Load **20 µg** of protein per well and run on SDS-PAGE gels in the Mini-PROTEAN system.
5. Probe the blots with the primary antibodies, then with the Odyssey secondary antibodies.
6. Image on the Odyssey CLx.
7. Normalise the signal of each protein to β-ACTIN and present it relative to the average of the controls.

## Not stated in the paper

- the transfer, blocking and wash conditions
- the primary antibody dilutions on the blot (the paper says the antibodies were used "as explained above")
- the membrane type and the imaging intensity settings

## Related protocols

01 SH-SY5Y, 15 immunocytochemistry, 26 chemiluminescent western blot, 44 statistics.
