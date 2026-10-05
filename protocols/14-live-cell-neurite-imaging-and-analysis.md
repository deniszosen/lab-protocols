# 14. Live-cell neurite imaging and automated neurite analysis

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571). Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056). Yadav et al. 2021, [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007). Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130) |
| Role of the Zosen Lab PI | First author of the 2023 paper. Contributing or second author on the others. |
| Licence | CC BY 4.0 |

## Purpose

Follow neurite outgrowth in the same wells over time by phase-contrast time-lapse imaging, and quantify neurite length and branching automatically. Two analysis routes are described: the IncuCyte NeuroTrack module and the in-house ANDA pipeline.

## Materials

- IncuCyte ZOOM live-cell analysis system (Essen BioScience), with the NeuroTrack software module (9600-0010). The 2022 paracetamol study also used an IncuCyte S3 for NT2N neurons.
- TPP 96-well plates (TPP Techno Plastic Products AG, 92096 or Sigma Z707910), coated as in protocol 08.
- ImageJ and the ANDA pipeline (Automated Neuronal Differentiation Analyzer, https://github.com/EskelandLab/ANDA), with a WEKA segmentation model per cell type.

## Procedure

1. **Seed and treat.** Seed the cells into coated 96-well plates (protocols 01, 02, 03 and 04) and treat them as the design requires (protocol 13).
2. **Image.** Place the plate in the IncuCyte at 37 °C and 5% CO2 immediately after treatment. Take four images per well with the 10× objective. Use the schedule below.
3. **Analyse** with NeuroTrack or ANDA, using the settings below.

### Imaging schedules used in the papers

| Study | Cells | Seeding | Scanning |
|---|---|---|---|
| 2023 | SH-SY5Y neurons | 1.5 × 10^4 cells per well in 150 µL, after re-seeding on DIV 17 | every 4 hours for 48 hours |
| 2025 | Chicken CGNs | 1.7 × 10^5 cells per well, exposed 24 hours after plating | every 4 hours for 68 hours |
| 2021 | PC12 | 0.8 × 10^4 cells/cm² with NGF, 1.6 × 10^4 cells/cm² without NGF | every 60 minutes for 72 hours |
| 2022 | CGNs and NT2Ns | per protocols 02 and 04 | every 90 minutes for 72 hours |

### NeuroTrack settings used

| Setting | SH-SY5Y (2023) | CGNs (2025) | PC12 (2021) |
|---|---|---|---|
| Segmentation | Texture | adjustment 0.5 | Texture |
| Hole fill | 0 | 0 | 0 |
| Adjust size | −5 µm | 0 | 5 (the text prints "5 mm"; verify the unit) |
| Min cell width | 8 µm | 7 µm | 8 (printed "8 mm"; verify) |
| Neurite filtering | Best | Best | Best |
| Neurite sensitivity | 0.35 µm | 0.65 | 0.35 (printed "0.35 mm"; verify) |
| Neurite width | 1 µm | 1 µm | 1 (printed "1 mm"; verify) |

### Quantities calculated

- **Neurite length** = sum of the lengths of all neurites pooled / area of the image field (2023 and 2021). The 2025 paper chose neurite length as the primary endpoint because it reflects neuronal differentiation and connectivity, which monoaminergic signalling influences during development.
- In the PC12 work (2021) also: **neurite branch points** = total number of branch points / area of the image field. **Cell-body clusters** = number of clusters / area. **Cell-body cluster area** = sum of cluster areas / area.

### The ANDA pipeline (2022)

- ANDA works with ImageJ and WEKA-segmented time-series phase-contrast images. It quantifies neurite length and branch points and other neuronal morphometrics.
- Train a WEKA classification model for each cell type on an image of an untreated sample 72 hours after seeding.
- To validate ANDA, the study analysed the CGN data set with NeuroTrack and compared the two result sets. The NeuroTrack module was trained on three images per time point of untreated CGNs at 6, 24, 48 and 72 hours after seeding. The parameters are in Table S1 of the paper.
- Replicates: CGNs, four wells per treatment with four images per well per time point. NT2Ns, twelve wells per treatment with four images per well per time point.

## Statistics as reported

- SH-SY5Y and CGNs: mean ± SEM, using all time points as repeated measures (GraphPad 8.2 and 10.2).
- PC12 (2021): a mixed model in JMP Pro 14 on log-transformed variables. Fixed effects: exposure group, time in culture and their interaction. Random effects: experiment and time nested within experiment. Dunnett's test against the solvent control. The effect of NGF was tested in a separate mixed model on the controls only.
- CGNs and NT2Ns (2022): two-way ANOVA with Dunnett's test (protocol 44).

## Not stated in the papers

- the ANDA settings and the macro (in the supplement and the GitHub repository)
- how well-to-well differences in seeding density are handled

## Related protocols

01 to 04 cell models, 08 coating, 13 compound exposure, 44 statistics.
