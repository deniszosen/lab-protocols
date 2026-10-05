# 15. Immunocytochemistry in plate-based and coverslip cultures

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Antibody tables in the supplements are not reproduced. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571). Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130). Saparova et al. 2019, [doi:10.1007/s11055-019-00799-9](https://doi.org/10.1007/s11055-019-00799-9) |
| Role of the Zosen Lab PI | First author (2023), contributing author (2022), second author (2019). |
| Licence | CC BY 4.0 |

## Purpose

Label proteins in fixed cultured cells and read the signal by imaging or on a plate reader. Three variants cover methanol-fixed neuronal cultures in 96-well plates, plate-reader quantification, and formalin-fixed stem cell coverslips.

## Variant A: SH-SY5Y neurons, methanol fixation (2023)

1. Seed neurons on black 96-well plates with a transparent bottom (lumox, Sarstedt 94.6120.096) at 1.5 × 10^4 cells per well.
2. Wash once with 1× PBS and fix with ice-cold 99% methanol for 10 minutes. Store at −20 °C until staining.
3. Wash three times with cold 1× PBS.
4. Block in 1× PBS with 0.05% Tween 20, 2.5% BSA and 1% normal goat serum, for 1 hour at room temperature or overnight at 4 °C.
5. Replace with blocking solution containing the primary antibodies and incubate overnight at 4 °C: rabbit anti-TUBB3 (1:2000, Sigma T2200) and mouse anti-GFAP (1:1000, Cell Signaling 3670).
6. Wash three times with cold PBS. Incubate with secondary antibodies for 1 hour at room temperature: goat anti-rabbit Alexa Fluor Plus 488 (Thermo A32731) and goat anti-mouse Alexa Fluor Plus 594 (Thermo A32742), both 1:1000.
7. Wash three times with PBS and keep in PBS at 4 °C until imaging.
8. Image at 10× on the IncuCyte ZOOM with exposure times of 550 ms (green) and 950 ms (red).
9. For MAP2 (1:5000, Abcam Ab5392), synaptophysin (1:200, Abcam Ab14692), PSD-95 (1:300, Abcam Ab13552) and DAPI (1:1000, Thermo 62248), the paper followed a previously published method (Lauvås et al. 2022) and imaged on a CellInsight CX7 High Content Analysis Platform (Thermo).

## Variant B: CGNs and NT2Ns, plate-reader quantification (2022)

1. Seed cells in black-frame clear-bottom 96-well plates (Corning CellBIND 3340 or 3603) with PLL and Geltrex coating (protocol 08), and treat them.
2. Aspirate the medium and rinse with room-temperature PBS. Fix with −20 °C 99% methanol for 10 minutes at −20 °C. Add cold PBS directly into the methanol before removing it, so the cells do not dry.
3. Discard the fixative and rinse three times with cold PBS.
4. Block overnight at 4 °C in TBST (TBS with 0.05% Tween 20) containing 2.5% BSA.
5. Incubate for 1 hour at room temperature on an orbital shaker with primary antibodies in blocking buffer: mouse anti-SPTBN1 (BD Transduction Laboratories 612562, 1:50) and rabbit anti-TUBB3 (Sigma T2200, 1:2000).
6. Wash 3 × 5 minutes with TBST. Incubate for 1 hour at room temperature on a shaker with goat anti-rabbit Alexa 488 (Invitrogen A-11070) and donkey anti-mouse Cy5 (Jackson ImmunoResearch 715-175-151), both 1:1000.
7. Wash 3 × 5 minutes with TBST, rinse with PBS and keep in PBS at 4 °C until imaging (2 to 48 hours). Before imaging, rinse with PBS and replace the PBS, to remove solvated fluorophores.
8. **Controls.** Include wells with no antibodies, with primary antibodies only, and with secondary antibodies only.
9. **Image** at 20× on the IncuCyte S3 with exposure times of 550 ms (green) and 950 ms (red).
10. **Quantify** the fluorescence on a CLARIOstar Plus plate reader with a dichromatic scan: 488 (488-14/535-30 nm ex/em) and Cy5 (610-30/675-50 nm ex/em), orbital averaging levels 0 to 6 at the maximum number of flashes, 570 flashes per well in total. Use three wells per treatment.
11. **Count TUBB3 punctae** by ImageJ particle analysis on the IncuCyte fluorescence images: three wells per treatment with nine images per well.
12. **Normalise.** Divide the fluorescence values and the TUBB3 counts by the matching DNAq values (protocol 34), to correct for cell loss between treatments. For the 144- and 216-hour NT2N experiments and for the caspase inhibitor experiments, normalise SPTBN1 to the matching TUBB3 values instead, because the study found these covaried with DNAq.

## Variant C: hippocampal neural stem cells on coverslips (2019)

1. Fix coverslips in 4% formalin.
2. Block non-specific binding in 5% normal goat serum in PBS with 0.3% Triton X-100.
3. Incubate with primary antibodies: Sox2 (1:1000), nestin (1:200), MAP-2 (1:200) and GFAP (1:250) (Neural Stem Characterization Kit, Millipore SCR019), doublecortin (1:400, Cell Signaling 4604), VGLUT2 (1:300, Millipore MAB5504), tyrosine hydroxylase (1:1000, Abcam ab6211), NeuN (1:500, Cell Signaling 12943) and BrdU (Roche 11170376001).
4. Detect with Alexa Fluor 568 anti-rabbit (1:1000, Invitrogen 762708) or Alexa Fluor 488 anti-mouse (1:1000, Invitrogen 913909). Stain nuclei with DAPI (1:2000, Sigma 28718-90-3).
5. Image on a Leica DMI 6000 B fluorescence microscope. Count cells in ImageJ against DAPI-stained nuclei, and score colocalisation (Sox2/nestin, MAP-2/GFAP, BrdU/GFAP, BrdU/TH, BrdU/NeuN).

## Not stated in the papers

- the incubation volumes and the wash volumes
- the secondary-only control results
- the antibody dilutions for BrdU and for the coverslip variant secondary controls
- the antibody tables of the supplements

## Related protocols

01, 02, 04, 05 cell cultures, 08 coating, 14 live imaging, 34 DNAq assay.
