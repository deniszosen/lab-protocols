# 25. Whole-cell patch-clamp recording and dye-fill morphology reconstruction in intact organoids

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. The recordings were done at the NDEVOR laboratory by collaborators. This protocol documents the method for reference and training. Not yet validated in the Zosen Lab. |
| Source paper | Ievglevskyi et al. 2026, [doi:10.1021/acschemneuro.5c00823](https://doi.org/10.1021/acschemneuro.5c00823) |
| Role of the Zosen Lab PI | Second author. Generated the organoids that were recorded (protocol 07). |
| Licence | CC BY 4.0 |

## Purpose

Record the electrical properties of neurons inside intact spinal cord organoids at DIV 15, 24 and 32, and reconstruct the shape of the recorded neurons from dye fills.

## Before you start

Organoids come from protocol 07. Recording requires a trained user and an electrophysiology rig. The original recordings were made at the Laboratory for Neural Development and Optical Recording (NDEVOR), University of Oslo.

## Materials

| Item | Details as stated |
|---|---|
| Bath solution (ACSF), room temperature | In mM: 150 NaCl, 5 KCl, 11 glucose, 1 MgSO4, 2 CaCl2, 10 HEPES; pH 7.4; 310 to 320 mOsm/L |
| Internal (pipette) solution | In mM: 117.5 K-gluconate, 17.5 KCl, 10 HEPES, 0.2 EGTA, 5 Mg-ATP, 0.5 Na3GTP, 10 Na-phosphocreatine; pH 7.4; 300 to 310 mOsm/L |
| Dye | Alexa Fluor 488 added to the pipette solution at about 20 µM |
| Electrodes | Borosilicate glass capillaries, outer diameter 1.5 mm (Sutter Instruments), pulled on an automated puller (PC-10, Narishige) |
| Rig | Multiclamp 700B amplifier (Molecular Devices), DigiData 1322A, WinWCP software |
| Visualisation | Upright IR-DIC microscope (Olympus BX51WI) with a CoolSNAP EZ camera. Fluorescence imaging with a 40× water-immersion objective (NA 0.8), a xenon light source with shutter control (VCM-D1 Uniblitz) and excitation at 482 ± 20 nm. |
| Analysis | pCLAMP 10, OriginLab 8, custom Python scripts (JupyterLab), Fiji/ImageJ and GIMP |

## Procedure

### Recording

1. Transfer an intact organoid from its culture well to the recording chamber with room-temperature ACSF. The recorded organoids had a diameter of 200 to 600 µm.
2. Identify neurons by IR-DIC and capture a DIC image of each recorded neuron at the start of the experiment.
3. Fill the electrode with the internal solution including Alexa Fluor 488.
4. Make whole-cell recordings. Filter the signals with a low-pass corner frequency (−3 dB) of 5 to 6 kHz and sample at 8 to 9 kHz.
5. **Voltage clamp:** record inward and outward currents carried by voltage-gated Na+ and K+ channels.
6. **Current clamp:** assess passive membrane properties and record resting membrane potentials and action potentials.
7. Control the amplifier and acquire data with WinWCP.

### Morphology reconstruction

8. Take fluorescence images of the dye-filled neuron (excitation at 482 ± 20 nm, 0.9 s exposure, 40× water-immersion objective). The paper describes the imaging as TIRF microscopy on the Olympus BX51WI.
9. Collect 2D or 3D images. The study processed fluorescence images from 106 of 134 recorded neurons and made a 3D reconstruction of 32 neurons.
10. Analyse the images in Fiji/ImageJ and GIMP.

## What was reported

The recordings showed progressive maturation between DIV 15 and DIV 32: hyperpolarised resting membrane potentials, larger inward currents, refined action potential kinetics and early mature-type firing. Spike frequency adaptation, typical of motor neurons, appeared at early stages (paper abstract).

## Statistics as reported

Mean ± SEM, one-way ANOVA with post hoc Bonferroni tests for pairwise comparisons (p < 0.05), in OriginLab 8 and custom Python scripts (protocol 44).

## Not stated in the paper

- the recording temperature and the perfusion rate
- the criteria for a healthy cell and for accepting a recording
- the step protocols for current and voltage
- how the organoid is held in the chamber

## Related protocols

07 organoid generation, 19 organoid immunostaining, 24 patch clamp in cultured neurons.
