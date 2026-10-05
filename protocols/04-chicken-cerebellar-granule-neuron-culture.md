# 04. Primary culture of chicken cerebellar granule neurons (CGNs)

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2022, [doi:10.1016/j.ntt.2021.107057](https://doi.org/10.1016/j.ntt.2021.107057) (main source). Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130) (variant). Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) (use) |
| Role of the Zosen Lab PI | First author of the 2022 paper, where the method is described in detail. |
| Licence | CC BY 4.0 |

## Purpose

Isolate cerebellar granule neurons from embryonic day 17 (E17) chicken cerebella and keep them as a primary culture for neurite, viability, reporter and exposure experiments.

## Before you start

- **Animal approval.** The papers state that a chicken embryo counts as an animal from embryonic day 14 (E14), so E17 embryos need an approved project. The approval number quoted in the papers (FOTS id 13,896) belongs to the original study. Your project needs its own approval. See chapter 11 of the [lab handbook](https://github.com/deniszosen/lab-handbook) and protocol 10.
- Work in a biosafety cabinet with sterile instruments. Record the egg supplier, the incubator and the embryonic day for every batch.

## Materials

| Item | Details as stated |
|---|---|
| Eggs | Fertilised Ross 308 broiler eggs (55 to 60 g), Nortura Samvirkekylling, Våler, Norway. Incubated at 37.5 °C and 45% humidity (protocol 10). |
| Physiological solution PS1 | 1× Krebs-Ringer solution with 3 g/L BSA and 306 mg/L MgSO4 (Labba 2022: BSA from Cytiva SH30574.02 and 2.54 mM MgSO4) |
| PS2 | PS1 plus 95 µg/mL trypsin inhibitor (Sigma T9003) and 22.5 µg/mL DNase I (Sigma D5025) |
| PS3 | PS1 plus 0.3 mg/mL MgSO4 and 96 µg/mL CaCl2 (Labba 2022: CaCl2 to 650 µM and MgSO4 2.82 mM) |
| Trypsin | 0.25 mg/mL in PS1 (Labba 2022: 250 µg/mL, Sigma T9201) |
| Plating medium (DIV 0) | BME (Gibco 41010-026) with 7.5% heat-inactivated chicken serum (Gibco 16110082), 25 mM KCl (including 3 mM from BME), 2 mM L-glutamine (Sigma G8540), 100 nM insulin (Sigma I5500), 1% penicillin-streptomycin (ThermoFisher 15070063) |
| Defined medium (from DIV 1) | BME with 25 mM KCl, 2 mM L-glutamine, 100 µg/mL holo-transferrin (Sigma 616397), 9.6 µg/mL putrescine (Sigma P5780), 30 nM Na2SeO3 (Sigma S5261), 1 nM T3 (Sigma T6369), 25 µg/mL insulin, 1% penicillin-streptomycin |
| Coating | Poly-L-lysine, 3 µg/cm² (protocol 08) |

## Procedure

1. **Collect.** Take E17 embryos from the incubator. Anaesthetise them in ovo by hypothermia (the eggs in crushed ice for 7 minutes), then remove the cerebella. Pool the cerebella of 15 to 20 embryos for each isolation (Labba 2022: 5 to 20).
2. **Mince.** Cut the cerebella with a scalpel in PS1. Labba 2022 adds mechanical trituration with a pipette.
3. **Wash.** Wash once and centrifuge at 200 RCF for 1 minute in an excess volume of PS1.
4. **Digest.** Resuspend the pellet in 0.25 mg/mL trypsin in PS1 for 15 minutes at 37 °C, shaking periodically.
5. **Stop the digestion.** Add four volumes of PS2 and centrifuge at 200 RCF for 2 minutes. Add one more volume of PS2 and resuspend until no tissue clumps remain.
6. **Wash.** Wash in an excess of PS3 and centrifuge at 200 RCF for 7 minutes.
7. **Coat the plates.** Coat with 3 µg/cm² poly-L-lysine in MQ water for 60 minutes, then air-dry before plating.
8. **Plate (DIV 0).** Seed in plating medium at 37 °C and 5% CO2. The 2022 paper used 35 mm dishes at 2.5 × 10^5 cells/cm². Labba 2022 used 530,000 cells/cm². Kaplan-Arabaci 2025 used 1.7 × 10^5 cells per well in TPP 96-well plates for neurite and viability assays.
9. **Change medium (DIV 1, 24 hours after seeding).** Switch to defined medium.
10. **Expose.** The 2025 paper exposed cells 24 hours after plating. Labba 2022 exposed in defined medium containing 10 µM cytosine β-D-arabinofuranoside (AraC, Sigma C1768) to limit glial proliferation. Make stock solutions as in protocol 13.

## Variants between the papers

| | Zosen 2022 | Labba 2022 |
|---|---|---|
| KCl in medium | 25 mM | 22 mM |
| Cerebella pooled | 15 to 20 embryos | 5 to 20 embryos |
| Seeding density | 2.5 × 10^5 cells/cm² | 530,000 cells/cm² |
| Glial control | Not stated | 10 µM AraC in treatment medium |
| Second coating | Not used | Geltrex on PLL for imaging by immunocytochemistry (protocol 08) |

## Replicate definition

Labba 2022 defines an independent CGN population as a culture from a unique set of embryonic cerebella. Use the same rule for n.

## Not stated in the papers: set and record these

- the mechanical dissociation steps in the 2022 paper (the wording only says the tissue was minced, and then the pellet was resuspended)
- the trypsinisation temperature control and shaking interval
- how cell number and viability are counted before plating
- the purity of the culture (the papers do not report a marker check in the Methods)

## Related protocols

08 coating, 09 spheroid migration, 10 chicken embryo handling, 14 neurite imaging, 29 luciferase assay, 33 MTT assay.
