# 13. Compound stocks, vehicle controls and exposure design

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Collected from the Methods of six papers. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2023, Kaplan-Arabaci et al. 2025, Zosen et al. 2021, Zosen et al. 2022, Labba et al. 2022, Yadav et al. 2021. DOIs are in [docs/source-papers.md](../docs/source-papers.md). |
| Licence | CC BY 4.0 |

## Purpose

How the papers prepared drug and chemical stocks, chose controls and designed exposure series, so every compound is handled in the same documented way.

## Before you start

- Read the safety data sheet of every compound. The lab studies compounds that can harm development. Handle powders and concentrated stocks as the risk assessment says. See chapter 12 of the [lab handbook](https://github.com/deniszosen/lab-handbook).
- **Link the dose to people.** Chapter 7 of the handbook asks you to record the concentration, the vehicle and the exposure time, to measure the concentration when you can, and to say how it relates to human exposure.

## Stock preparation as reported

| Compound | Source and preparation |
|---|---|
| Escitalopram oxalate, venlafaxine hydrochloride | Tocris 4796 and 2917. 50 mM in sterile ddH2O, aliquoted and stored at −20 °C, used fresh without freeze-thaw cycles (2023 and 2025 papers). |
| Serotonin hydrochloride, L-norepinephrine hydrochloride | Sigma H9523 and 74480. 10 mM stocks in sterile ddH2O, stored at −20 °C (2023). |
| Valproic acid sodium salt, lamotrigine isethionate | Sigma P4543, Tocris 2289 (2021) or Sigma SML1082 (2022). Dissolved in saline before injection. |
| Acetaminophen (APAP) | Sigma A7085. 100 mM stock in MQ water by vortexing at 37 °C, sterile-filtered, aliquoted and stored at −20 °C, protected from light, never freeze-thawed (2022). |
| Caspase-3 inhibitor | Calbiochem, CAS 285570-60-7. 1 mM stock in MQ water, used at 1 µM final (2022). |
| Retinoic acid | 20 mM stock in DMSO (BioGems 3027949) (2023). |
| PFOS | Perfluorooctanesulfonic acid potassium salt (≥98%, Sigma), DMSO solvent (2021). |
| POP mixture | 29 compounds: six perfluorinated (PFHxS, PFOS, PFOA, PFNA, PFDA, PFUnDA), seven brominated (PBDE-47, -99, -100, -153, -154, -209 and HBCD) and sixteen chlorinated (PCB-28, -52, -101, -118, -138, -153, -180, p,p'-DDE, HCB, α-chlordane, oxychlordane, trans-nonachlor, α-, β- and γ-HCH, dieldrin). The relative amounts follow Scandinavian human blood levels. Stocks were 10^6 times the measured human blood levels in DMSO, made at the Norwegian University of Life Sciences (Berntsen et al. 2017). Used at 10 to 500 times human blood levels. |

**Check units in the POPs paper.** The text layer of that paper prints "mM" and "mL" in places where "µM" and "µL" are clearly meant (for example "10 to 100 mM" PFOS in a cell toxicity test). Verify every unit against the typeset PDF.

## Exposure designs as reported

| Study | Design |
|---|---|
| SH-SY5Y neurons | 48 hours of exposure from DIV 19, with readouts on DIV 21 (protocol 01) |
| Chicken CGNs | Exposure 24 hours after plating. Escitalopram 1, 10 and 100 µM, venlafaxine 2, 20 and 200 µM (2025). VPA 100, 500 and 1000 µM, LTG 1, 10 and 100 µM (2022). |
| Chicken embryos | Single injection into the allantois at 1 µL per gram of egg (protocol 10) |
| NT2N and CGN, APAP | Four-step series from 100 to 1600 µM in defined medium. Controls and all concentrations below 1600 µM receive MQ water so every well has the same dilution of the medium. For experiments longer than 72 hours, refresh half the volume every third day with medium that contains the sample-appropriate APAP concentration. For experiments of 72 hours or less, do not disturb the cells. |
| PC12 | 72 hours with 0.1% DMSO solvent control, with and without NGF. PFOS 10 to 100 µM in the toxicity tests and 10 to 50 µM for neurite outgrowth (units to verify, see the note above), since concentrations above 50 µM had no effect on neurite outgrowth in preliminary studies and were associated with fewer cells. |

## Controls used in the papers

- Solvent or vehicle control for every compound (0.1% DMSO in the PC12 work, saline in the embryo work).
- Non-injected eggs, in the chicken embryo study of 2022.
- Positive controls: valinomycin (15 µM) for mitochondrial toxicity in PC12 (protocols 17 and 33), 1 mM H2O2 for the MTT assay (protocol 33), NMDA with glycine, and the antagonist (+)-MK-801 in the Fura-2 control experiments (protocol 18).

## Procedure

1. Choose the compound, the vehicle, the concentration series and the exposure window before you start. Write them into the project README (handbook, chapter 7).
2. Prepare stocks as in the table. Aliquot, label with the date and the lot, and keep them away from freeze-thaw cycles.
3. Dilute into the exposure medium on the day of use.
4. Equalise the vehicle across every group.
5. Include the controls for the assay.
6. Record the final concentration of each compound and of the vehicle.

## Not stated in the papers

- the maximum DMSO concentration allowed in all studies
- the stability testing of the stocks
- how the exposure medium concentration was verified (measure it by mass spectrometry where you can: protocols 36 to 38)

## Related protocols

01 SH-SY5Y, 03 PC12, 04 CGNs, 10 chicken embryo exposure, 17 high-content assay, 18 calcium imaging, 33 MTT assay, 36 to 38 drug quantification.
