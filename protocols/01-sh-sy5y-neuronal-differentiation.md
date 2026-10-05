# 01. Neuronal differentiation of SH-SY5Y cells

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571) (main source). Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) (variant) |
| Role of the Zosen Lab PI | First author of the 2023 paper, who built and validated the culture. Second author of the 2025 paper, who ran the human cell work. |
| Licence | CC BY 4.0 |

## Purpose

Turn human neuroblastoma SH-SY5Y cells into a neuron-like culture with all-trans retinoic acid (RA) over 21 days, then re-plate the cells for drug exposure and for imaging, biochemical, calcium and electrophysiological readouts on day in vitro (DIV) 21.

## Before you start

- Read chapters 7 and 8 of the [lab handbook](https://github.com/deniszosen/lab-handbook). Record the cell source, passage number and authentication in your notebook.
- Test the culture for mycoplasma before you start and at the interval the lab sets. The paper does not state a schedule.
- Work in a class II biosafety cabinet and treat human-derived cells as potentially infectious.
- Wear gloves and a lab coat. Retinoic acid is a developmental toxicant. Read its safety data sheet and handle the powder and DMSO stock with the controls the risk assessment names.

## Materials

| Item | Details as stated in the paper |
|---|---|
| Cells | SH-SY5Y, ATCC CRL-2266. Use passages 9 to 15. Split at least twice after thawing before you start differentiation. |
| Growth medium | DMEM with L-glutamine (Thermo 42430025), 10% FBS (Lonza DE14801F), 1% pyruvate (Thermo, printed as "1360-070" in this paper; the paracetamol paper prints 11360-070 for the same reagent, so confirm the catalogue number before you order), 1% penicillin-streptomycin (Thermo 15140-122) |
| Differentiation medium | Same base with 1% FBS, 1% pyruvate, 1% penicillin-streptomycin and 10 µM all-trans retinoic acid (20 mM stock in DMSO, BioGems 3027949) |
| Detachment | Accutase (Thermo A1110501) |
| Coating | Poly-L-lysine hydrobromide (Sigma P2636) and Cultrex Basement Membrane Matrix (Bio-Techne 3434-010-02). See protocol 08. |
| Viability probe | NeuroFluor NeuO (STEMCELL Technologies 01801) |
| Plastic | 100 mm dishes for expansion and differentiation. 6-, 24- or 96-well plates for assays (see step 7). |

## Procedure

1. **Expand.** Thaw the cells and grow them on 100 mm dishes in growth medium. Split them at least twice after thawing and use them at passage 9 to 15.
2. **Start differentiation (DIV 0).** When the culture reaches about 70 to 80% confluence, replace the growth medium with differentiation medium.
3. **Feed.** Refresh the medium every Monday, Wednesday and Friday for 21 days. The paper counts this period as DIV 0 to 21.
4. **Watch the morphology.** At about DIV 14 the cells change to a more neuron-like shape, with visible neurites and clustering. Record images.
5. **Harvest (DIV 17).** Incubate with Accutase for 5 minutes at 37 °C and spin at 900 rpm for 5 minutes. One 100 mm dish gave about 5 to 15 × 10^6 cells in the paper.
6. **Prepare the plates before harvest.** Coat with 5 µg/cm² poly-L-lysine in ddH2O for 1 hour at room temperature, remove it and air-dry. Then add 5 µg/cm² Cultrex in ice-cold DMEM for 1 hour at 37 °C and discard it immediately before seeding.
7. **Re-plate (DIV 17).** Seed at the density that suits the assay. The paper used:
   - immunofluorescence: 1.5 × 10^4 cells per well, black 96-well plates with a transparent bottom (lumox, Sarstedt 94.6120.096)
   - neurite imaging: 1.5 × 10^4 cells per well in 150 µL, TPP 96-well plates
   - Fura-2 calcium measurement: 2 × 10^4 cells per well, black 96-well plates with a glass bottom
   - luciferase reporter: 7 × 10^5 cells per well, 6-well plates
   - electrophysiology: 2 × 10^5 cells per well, 24-well plates holding 12 mm round glass coverslips coated with poly-L-lysine and Cultrex
   - western blot: 6-well plates (the density is not stated)
8. **Check the culture.** The paper reports more than 99% live neurons, confirmed with 20 nM NeuO for 1 hour at 37 °C. Do this on a sample plate for every batch.
9. **Expose (DIV 19).** Start exposure to test compounds on DIV 19, in differentiation medium, for 48 hours. Make stock solutions as in protocol 13. The paper dissolved escitalopram and venlafaxine at 50 mM in sterile ddH2O, stored them at −20 °C and used them fresh without freeze-thaw cycles.
10. **Read out (DIV 21).** Assess the effects on DIV 21 with the assays in protocols 14, 15, 18, 24, 26, 27, 29 and 33.

## Quality checks

- From the paper: morphology change by DIV 14 and neuronal markers at DIV 21 (TUBB3, MAP2, synaptophysin, PSD-95). The paper also stains GFAP to look for glial cells. Staining methods are in protocol 15.
- More than 99% live cells by NeuO.
- Keep an untreated, undifferentiated SH-SY5Y control for comparison, as the paper did for electrophysiology and for the synaptic protein western blot.

## Variants between the two papers

| | Zosen 2023 | Kaplan-Arabaci 2025 |
|---|---|---|
| Growth medium | DMEM, 10% FBS, 1% pyruvate, 1% penicillin-streptomycin | DMEM, 10% FBS, 1% non-essential amino acids, penicillin-streptomycin |
| RA | 10 µM | 10 µM |
| Duration | 21 days, with re-plating at DIV 17 | The text says 17 days |

Use the 2023 version unless you have a reason to follow the 2025 one, and write the choice into your notebook.

## Not stated in the paper: set and record these before you use the protocol

- passaging ratio and seeding density for routine expansion
- whether routine passaging used trypsin or Accutase
- the schedule for mycoplasma testing and cell authentication
- final DMSO concentration from the RA stock
- whether the RA stock is protected from light
- seeding density for the western blot plates

## General practice notes (not from the paper)

> Prepare RA aliquots in the dark and use them once. Keep a differentiation log with passage number, start date, medium lot and any deviation. Plan the differentiation start so that DIV 17 and DIV 19 do not fall on a weekend.

## Related protocols

08 coating, 13 compound exposure, 14 neurite imaging, 15 immunocytochemistry, 18 calcium imaging, 24 patch clamp, 26 and 27 western blot, 29 luciferase assay, 33 MTT assay.
