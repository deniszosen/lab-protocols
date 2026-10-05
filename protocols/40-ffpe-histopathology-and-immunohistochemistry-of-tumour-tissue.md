# 40. FFPE histopathology and immunohistochemistry of tumour tissue, with digital scoring

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Reference method. The work was done by clinical partners in Moscow and is recorded here for the analysis side. Not planned for the Zosen Lab. |
| Source paper | Anoshkin et al. 2022, [doi:10.1016/j.heliyon.2022.e10291](https://doi.org/10.1016/j.heliyon.2022.e10291) |
| Role of the Zosen Lab PI | Second author. Took part in the data analysis. The laboratory and pathology work was done at the Research Centre for Medical Genetics, Moscow. |
| Licence | CC BY 4.0 |

## Purpose

Show how a surgical tumour specimen is fixed, stained and scored (H&E, automated immunohistochemistry, digital slide review, mitotic count, Ki67 index), so that new members understand the clinical pathology that sits behind molecular results.

## Before you start

- Human tissue needs ethical approval, informed consent and a data protection basis. The original study was approved by the Ethics Committee at the Research Centre for Medical Genetics, Moscow, and the patient's guardian gave written consent, including consent to publish the data. None of this transfers to a new project.
- Do not handle patient samples in the Zosen Lab without your own approvals from the relevant ethics committee, the biobank and the data protection officer.

## Materials (as in the paper)

- 10% buffered formalin. Paraffin embedding by a standard tissue processor.
- BONDMAX automated staining system, BOND Epitope Retrieval solutions 1 and 2, BOND Polymer Refine Detection Kit (Leica Biosystems).
- Antibodies: Pan-Cytokeratin (Leica PA0094), CD68 (Leica NCL-L-CD68), Brachyury (Abcam ab209665), EMA (Biogenex AMB78-5M), S100 (CellMarque 330M16), GFAP (Leica NCL-L-GFAP-GA5), Ki67 (Leica PA0118).
- Aperio AT2 slide scanner (200× absolute magnification). A digital pathology viewing platform.

## Procedure

1. Fix the whole surgical specimen (tumour fragments) in 10% buffered formalin.
2. Process and embed in paraffin to make FFPE blocks by a standard procedure.
3. Cut sections. Prepare H&E slides for diagnosis, and further sections for immunohistochemistry and molecular genetics (protocol 41).
4. Stain on the BONDMAX with the standard protocols, the Bond epitope retrieval solutions and the polymer detection kit, following each antibody vendor's recommendations.
5. Scan all slides at 200× absolute magnification (Aperio AT2) and upload them to the digital platform.
6. Two specialists review the slides on screen. Assess the morphology directly.
7. **Mitotic count**: count in a virtual circular area of 500 µm diameter (the average diameter of a field at 400× magnification).
8. **Ki67 index**: use the integrated Ki67 algorithm of the viewing platform (UNIM LTD, Moscow). An area is acceptable if it contains 500 to 1000 tumour cells. The index is the number of tumour cells with positive nuclear Ki67 staining divided by the total number of tumour cells in that area.
9. Mark three hotspot areas (those with the highest ratio of positive nuclei), measure each, and report the mean.

## What the paper reported for the case

The conventional chordoma pattern, with strong nuclear Brachyury, cytoplasmic EMA, S100 and Pan-Cytokeratin, no GFAP or CD68, and a Ki67 index of about 15% by manual and algorithmic scoring.

## Not stated in the paper

- the section thickness, the incubation times and the antibody dilutions
- the algorithm's validation data (it is proprietary)

## Related protocols

23 slide scanning and blinded scoring, 41 FFPE DNA and sequencing.
