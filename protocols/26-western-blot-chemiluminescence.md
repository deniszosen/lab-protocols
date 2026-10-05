# 26. Western blot with chemiluminescent detection (tissue and cell lysates)

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Collected from five papers with four lysis variants. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2022, [doi:10.1016/j.ntt.2021.107057](https://doi.org/10.1016/j.ntt.2021.107057). Zosen and Glazova 2016, [doi:10.1007/s11055-016-0277-y](https://doi.org/10.1007/s11055-016-0277-y). Zosen et al. 2018, [doi:10.1016/j.neulet.2018.06.056](https://doi.org/10.1016/j.neulet.2018.06.056). Saparova et al. 2019, [doi:10.1007/s11055-019-00799-9](https://doi.org/10.1007/s11055-019-00799-9). Dorofeeva et al. 2017, [doi:10.1134/S2079059717030029](https://doi.org/10.1134/S2079059717030029) |
| Role of the Zosen Lab PI | First author (2022, 2016, 2018), second author (2019), contributing author (2017). |
| Licence | CC BY 4.0 |

## Purpose

Measure protein levels and phosphorylation in lysates of tissue or cultured cells by SDS-PAGE, immunoblotting and chemiluminescent detection, and quantify the bands by densitometry.

## Before you start

Record the antibody catalogue number, lot and dilution in your notebook for every blot. Handle mercaptoethanol and acrylamide in a fume hood. Keep unprocessed blot images (handbook, chapter 7, images and figures).

## Variant A: cerebellar tissue lysate (2022)

1. Keep the cerebella on ice and homogenise them with a pellet pestle in TE buffer (10 mM Tris, 1 mM EDTA, pH 8) with three protease inhibitors (leupeptin 5 µg/µL, pepstatin A 1 µg/µL, PMSF 300 µM) and the phosphatase inhibitor Na3VO4 (300 µM).
2. Add SDS to 2% and homogenise through a 22G needle. Denature at 95 °C for 5 minutes.
3. Measure protein with the Pierce BCA Protein Assay Kit. Load **25 µg** per well.
4. Probe with primary antibodies against PAX6 (1:7500, Sigma AB2237), MMP-9 (1:3000, Enzo BML-SA680-0100), PCNA (1:1000, Dako M0879) and β-ACTIN (1:2000, Sigma A5316).
5. Detect with an HRP-conjugated secondary antibody (1:10000: goat anti-mouse IgG-HRP from Bio-Rad, donkey anti-rabbit IgG-HRP from Santa Cruz) and HRP substrates, in a Syngene gel documentation system.
6. Quantify in ImageJ as the total pixel intensity of the bands (integrated density tool) after background subtraction. Calculate the ratio of protein to β-actin and express it relative to the control average.

## Variant B: cultured cells in hot SDS buffer (2016 and 2019)

1. Lyse cells by adding **100 µL of hot 3× SDS buffer per 3.5 cm²** (one well of a six-well plate). The buffer per 100 mL: 2.42 g Tris-HCl pH 6.7, 6 g SDS (6%), 15 mL glycerol (15%), 3 mg bromophenol blue and 10% β-mercaptoethanol.
2. Collect the lysate, incubate at +95 °C for 10 minutes and store at −20 °C.
3. Separate proteins by SDS-PAGE (Laemmli system) and transfer to nitrocellulose membranes (Amersham, GE Healthcare).
4. Block in 3% defatted dried milk in TBS-T (0.1 M Tris/HCl pH 7.6, 0.15 M NaCl, 0.1% Tween-20) for 1 hour.
5. Incubate with primary antibodies (2016): p53 (1:2000, Abcam), p-p53 Ser315 (Novus), TH and p-TH, ERK1/2 and p-ERK1/2 Thr202/Tyr204 (1:1000, Cell Signaling), p-CREB Ser133 (1:1000, Cell Signaling), cRaf1 (1:1000, Cell Signaling), p-cRaf Ser338 (1:1000, Cell Signaling) and GAPDH (1:2000, Abcam), for 1 hour at 4 °C. In the 2019 paper the antibodies were GAD67 (1:10000, Millipore MAB5406) and GAPDH (1:10000, Abcam ab8245), overnight at 4 °C.
6. Wash in TBS-T. Incubate with HRP-conjugated anti-rabbit (1:8000) or anti-mouse (1:50000) secondary antibody (Sigma-Aldrich) in TBS-T.
7. Visualise with the ECL Plus system (Amersham). Estimate protein quantities by scanning films of at least three blots and analysing them in ImageJ, with background correction and normalisation to GAPDH. The 2016 paper used n = 8 per protein.

## Variant C: PC12 cells in SDS-stop buffer (2018)

1. Homogenise cells in SDS-stop buffer with 3% β-mercaptoethanol and denature at 95 °C for 5 minutes.
2. Separate on a 10% acrylamide/bis-acrylamide gel and transfer to nitrocellulose membranes.
3. Incubate overnight with the primary antibody: TH (Sigma T1299), p-TH Ser31 (Millipore AB5423), ERK1/2 (Cell Signaling 9102), pERK1/2 (Cell Signaling 4376), synapsin I (Millipore AB1543P), p-synapsin I Ser62/67 (Millipore AB9848), SNAP25 (Chemicon MAB331), VAMP-2 (Synaptic Systems 104221), p-CaMKII Thr286 (Thermo MA1-047), p-VASP Ser239 (Santa Cruz sc-101439) and p-VASP Ser157 (Santa Cruz sc-101440).
4. Incubate with an anti-rabbit or anti-mouse HRP secondary antibody and detect with SuperSignal West Dura Extended Duration Substrate (Thermo 34075).

## Variant D: rat brain regions (2017)

1. Extract protein from the striatum and the substantia nigra (protocol 12).
2. Resolve by SDS-PAGE (Laemmli) and transfer to a nitrocellulose membrane (Amersham, Freiburg).
3. Detect with the antibodies in protocol 22 and visualise with the ECL Plus system (Amersham).
4. Perform densitometry in ImageJ. Normalise protein levels to GAPDH. Normalise the phosphorylated forms of ERK1/2 and tyrosine hydroxylase to the total forms in the same samples.

## Not stated in the papers

- gel percentages, run times and transfer conditions for most variants
- the blocking step for variants A, C and D
- the secondary antibody dilution in variant C
- the exposure times for chemiluminescence and film

## Related protocols

03 PC12, 05 neural stem cells, 11 sample collection, 12 rat model, 27 infrared western blot, 44 statistics.
