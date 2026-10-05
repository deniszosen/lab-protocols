# 07. Generation of spinal cord organoids from human iPSCs

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. The paper cites "a previously published protocol" for the differentiation, and the details below are those printed in this paper. Not yet validated in the Zosen Lab. |
| Source paper | Ievglevskyi et al. 2026, [doi:10.1021/acschemneuro.5c00823](https://doi.org/10.1021/acschemneuro.5c00823) |
| Role of the Zosen Lab PI | Second author. Performed the organoid differentiation ("D.Z. performed organoid differentiation"). The electrophysiology and imaging were done by collaborators. |
| Licence | CC BY 4.0 |

## Purpose

Generate spinal cord organoids (SCOs) from human iPSCs by reaggregating single cells into embryoid bodies in U-bottom plates and patterning them with a timed schedule of small molecules and growth factors over 32 days in vitro (DIV).

## Before you start

- Complete the consent, approval and agreement checks in protocol 06. Record the iPSC line, its passage number and the batch of each reagent.
- Read chapters 7, 11 and 12 of the [lab handbook](https://github.com/deniszosen/lab-handbook). CHIR99021, SB431542, retinoic acid and Y-27632 are bioactive. Retinoic acid is a developmental toxicant.

## Materials

| Item | Details as stated |
|---|---|
| Cells | Human iPSCs at about passage 10 and 70 to 80% confluence (protocol 06) |
| Detachment | Accutase (ThermoFisher A1110501) |
| Plates | Ultralow-attachment U-bottom 96-well plates (Corning CLS7007) |
| Base medium (N2B27) | 1:1 DMEM/F-12 and Neurobasal medium (ThermoFisher), 0.5% (v/v) N2 supplement (ThermoFisher 17502001), 1% (v/v) B27 supplement without vitamin A (ThermoFisher 12587010), 1% MEM-NEAA, 1% GlutaMAX, 0.1 mM 2-mercaptoethanol, 0.5 µM ascorbic acid, 1% penicillin-streptomycin (ThermoFisher 15070063) |
| Seeding medium | N2B27 with 10% knockout serum replacement (KSR; ThermoFisher 10828010) |
| Y-27632 | AdooQ A11001 |
| CHIR99021 | Peprotech 2520691 |
| bFGF | Peprotech 100-18B, 20 ng/mL |
| SB431542 | Biogems 3014193 |
| Retinoic acid | Peprotech 3027949 |
| BMP4 | 15 ng/mL (the paper does not give the supplier) |
| BDNF | Peprotech 450-02, 10 ng/mL |
| GDNF | Peprotech 450-10, 20 ng/mL |

## Compound schedule

| Days in vitro | Additions to N2B27 |
|---|---|
| DIV 0 to 3 | 10 µM Y-27632, 3 µM CHIR99021, 20 ng/mL bFGF |
| DIV 0 to 6 | 10 µM SB431542 |
| DIV 3 to 15 | 100 nM retinoic acid |
| DIV 15 to 24 | 100 nM retinoic acid and 15 ng/mL BMP4 |
| DIV 15 to 32 | 10 ng/mL BDNF and 20 ng/mL GDNF |

The 10% KSR in the medium applies from DIV 0 to 15, as the paper states. Medium changes happen every 2 days.

## Procedure

1. **Dissociate (DIV 0).** Dissociate 70 to 80% confluent iPSCs at about passage 10 into single cells with Accutase.
2. **Reaggregate.** Seed 10,000 cells per well in 150 µL of N2B27 with 10% KSR into ultralow-attachment U-bottom 96-well plates. Add the DIV 0 to 3 compounds and SB431542 (see the schedule).
3. **Feed.** Change the medium every 2 days, adding each compound or factor only for the window shown in the schedule.
4. **Keep the KSR-containing medium until DIV 15.**
5. **Pattern.** Add retinoic acid from DIV 3, BMP4 from DIV 15 and BDNF with GDNF from DIV 15, as scheduled.
6. **Sample.** The study harvested organoids for staining at DIV 24 and DIV 32 (protocol 19) and recorded from organoids with a diameter of 200 to 600 µm at DIV 15, DIV 24 and DIV 32 (protocol 25).

## Quality checks

- General practice, not from the paper: check embryoid body formation in every well on DIV 1.
- Organoid size at the time of recording (the study used 200 to 600 µm).
- Expression of motor neuron and interneuron markers at DIV 24 and 32. The study reported ISLET1 and HB9 (motor neurons) and LHX1/5 and PAX2 (immature spinal interneurons), by immunostaining (protocol 19).
- General practice, not from the paper: keep the same line, passage and reagent lots across batches, and record any batch that fails the marker check.

## Not stated in the paper: set and record these

- the supplier of BMP4 and the lot numbers
- whether KSR is removed from the medium after DIV 15
- how organoids are moved from the U-bottom wells during the later weeks, and the medium volume at each change
- when Y-27632 is removed (the schedule says DIV 0 to 3)
- the plate format, or whether organoids stay in the original wells
- the reference of the "previously published protocol"

## Related protocols

06 iPSC maintenance, 19 organoid sectioning and immunostaining, 25 patch clamp in organoids.
