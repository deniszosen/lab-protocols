# 24. Whole-cell patch-clamp recording in cultured SH-SY5Y-derived neurons

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. Electrophysiology in this paper was done with collaborators. This protocol documents the method for reference and training. Not yet validated in the Zosen Lab. |
| Source paper | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571) |
| Role of the Zosen Lab PI | First author. Built and validated the neuronal culture that was recorded. |
| Licence | CC BY 4.0 |

## Purpose

Record sodium and potassium currents and action potentials from differentiated SH-SY5Y neurons, and compare them with undifferentiated cells, to show that the culture contains functional neurons.

## Before you start

Cells must be prepared as in protocol 01. Electrophysiology needs training on the rig by an experienced user (handbook, chapter 13). TTX is acutely toxic: follow the safety rules for it.

## Materials

| Item | Details as stated |
|---|---|
| Cells | SH-SY5Y neurons plated on DIV 17 on 12 mm round glass coverslips in 24-well plates (Nunclon 143982), coated with PLL and ECM (protocol 08), at 2 × 10^5 cells per well |
| Bath solution (ACSF) | In mM: 150 NaCl, 5 KCl, 1 MgSO4, 2 CaCl2, 10 glucose, 10 HEPES; pH 7.4; 300 to 310 mOsm/L |
| Pipette solution | In mM: 100 CsF, 40 CsCl, 5 NaCl, 0.5 CaCl2, 10 HEPES, 2 EGTA, 2 Mg-ATP. Aliquots made fresh and filtered. Osmolarity 290 mOsm/L. |
| Sodium channel blocker | Tetrodotoxin citrate (TTX), 1 µM (Alomone Labs T-550) |
| Microscope | Upright infrared differential interference contrast (IR-DIC) microscope (Olympus BX51WI) with a CoolSNAP EZ camera (Photometrics) |
| Electrodes | Borosilicate glass capillaries pulled with a vertical puller (PC-10, Narishige). Resistance 8 to 10 MΩ. |
| Amplifier and acquisition | Multiclamp 700B (Molecular Devices), DigiData 1322A, WinWCP software (University of Strathclyde) |
| Analysis | pCLAMP 10 (Molecular Devices) and OriginLab 8 |

## Procedure

1. On DIV 21, transfer a coverslip to a submersion chamber perfused with ACSF.
2. Find the neurons by IR-DIC.
3. Pull patch pipettes, fill with the pipette solution and check the resistance (8 to 10 MΩ).
4. Establish whole-cell recordings. Filter signals with a low-pass corner frequency (−3 dB) of 3 kHz and sample at 6 kHz.
5. **Voltage clamp:** record Na+ and K+ currents with the standard protocols. The holding potential is −60 mV unless stated otherwise.
6. **Current clamp:** apply step current injections to evoke action potentials.
7. Apply 1 µM TTX to confirm the TTX-sensitivity of the currents.
8. Repeat the procedure on undifferentiated SH-SY5Y cells for comparison.
9. Analyse in pCLAMP 10 and OriginLab 8. The same coverslips were then tested for spontaneous calcium transients (protocol 18).

## Not stated in the paper

- the seal and series resistance acceptance criteria
- the voltage and current step protocols ("the standard protocols")
- the temperature of the recording
- the number of cells and coverslips analysed

## Related protocols

01 SH-SY5Y neurons, 08 coating, 18 calcium imaging, 25 patch clamp in organoids.
