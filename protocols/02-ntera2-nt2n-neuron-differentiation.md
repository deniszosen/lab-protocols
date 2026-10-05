# 02. NTERA2 culture and differentiation into NT2N neurons in rotating spheroids

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from published methods. Not yet validated in the Zosen Lab. |
| Source paper | Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130). The authors modified the agitated spheroid method of Serra et al. 2007. |
| Role of the Zosen Lab PI | Contributing author. Differentiated the human NT2N neurons the study used and analysed that arm. |
| Licence | CC BY 4.0 |

## Purpose

Maintain human embryonal carcinoma NTERA2 cells and differentiate them with retinoic acid (RA) into pre-terminal NT2N neurons over 20 days in agitated spheroid culture. Then re-seed the neurons for exposure experiments.

## Before you start

- Read chapters 7 and 8 of the [lab handbook](https://github.com/deniszosen/lab-handbook). Record the source, passage number and mycoplasma status of the NTERA2 stock. The paper used mycoplasma-tested cells.
- Human-derived cells in a biosafety cabinet. Retinoic acid is a developmental toxicant: use the controls in the risk assessment.

## Materials

| Item | Details as stated in the paper |
|---|---|
| Cells | NTERA2, ATCC CRL-1973 |
| Maintenance medium | High-glucose, GlutaMAX DMEM (Gibco 42430-025), 10% FBS (Capricorn FBS-11A), 1 mM pyruvate (ThermoFisher 11360-070), 1% penicillin-streptomycin (ThermoFisher 15140-122) |
| Flask coating | Gelatin (Sigma G1890-500G), printed as "1.33 mg/cm2" in MQ water for 1 hour at room temperature. Check this figure before use: it is high for a gelatin coating and may be a unit slip. |
| Trypsin | Gibco 25300054 |
| Retinoic acid | all-trans RA, ThermoFisher R2625 |
| Defined medium | High-glucose, GlutaMAX DMEM/F12 (Gibco 31331-028), 2% B27 (ThermoFisher 17504044), 1% N2 (ThermoFisher 17502048), 1 mM pyruvate, 1% penicillin-streptomycin, 20 µM RA |
| Vessels | 75 cm² flasks (VWR 734-2313). 100 mm low-adhesion dishes. Orbital rotator (Infors HT Celltron 69222, 25 mm orbit). |
| Re-seeding vessels | PLL plus Geltrex (live imaging and immunocytochemistry) or PLL plus fibronectin (MTT). See protocol 08. |

## Procedure

### A. Maintenance

1. Coat 75 cm² flasks with gelatin for 1 hour at room temperature, remove the solution and wash with PBS.
2. Grow NTERA2 cells at 37 °C and 5% CO2 in 10 mL maintenance medium.
3. Every 3 days, at about 75% confluence: remove the medium, rinse with PBS, add 2 mL trypsin for 5 minutes at 37 °C and 5% CO2, then add 8 mL maintenance medium to stop the trypsin.
4. Triturate and re-plate 1 mL of the suspension (a 1:10 split). Discard the rest.

### B. Spheroid formation (RA-free)

5. Seed 10 mL of NTERA2 suspension at 5 × 10^5 cells/mL into 100 mm low-adhesion dishes in maintenance medium.
6. Incubate at 37 °C and 5% CO2 on the rotator at 60 rpm for 2 to 4 days, until spheroids form.
7. Collect the suspension and centrifuge at 200 RCF for 1 minute. Replace the medium with fresh maintenance medium every day, until the spheroids are visible to the naked eye.

### C. Differentiation (20 days, counted from the first RA exposure)

8. **Day 0.** Replace the medium with 10 mL maintenance medium plus 10 µM RA.
9. **Days 0 to 6, serum-containing phase.** Every 2 days, remove half the medium and add 5 mL fresh maintenance medium with 20 µM RA.
10. **Day 6.** Remove half the medium and replace the serum-containing medium with 5 mL defined medium containing 20 µM RA.
11. **Days 6 to 20, defined phase.** Every 2 days, change half the volume with defined medium. The paper calls the second phase 14 days in total.
12. Keep the cells as suspended rotating spheroids for the whole 20 days.

### D. Re-seeding

13. After 20 days, trypsinise the spheroids and seed the cells onto coated vessels at 50,000 cells/cm² in a 1:1 mixture of conditioned and fresh defined medium. The fresh half is supplemented with 10 µM RA.
14. Incubate overnight at 37 °C and 5% CO2 for attachment, then start treatment.
15. Use these coatings and plates:
   - MTT: Nunc 96-well plates, poly-L-lysine, then 320 ng/cm² fibronectin (ThermoFisher 33010018) applied in half of the seeding volume. Seed directly into the coating solution without removing it.
   - Live imaging and immunocytochemistry: poly-L-lysine and Geltrex, in Corning 3603 black, clear-bottom 96-well plates.
16. For the migration assay, see protocol 09.

## Quality checks and replicate definition

- The paper defined an independent NT2N population as a culture that was separately differentiated from NTERA2 cells grown for at least three serial or parallel passages. It also required a minimum of one month of time between independent cultures of the same type. Use the same definition for n.
- Add your own marker check at day 20 (for example TUBB3 by protocol 15). The paper does not describe a marker check for the NT2N cultures in the Methods.

## Not stated in the paper: set and record these

- passage number range for the NTERA2 stock
- how conditioned medium is collected and how much is kept
- the trypsinisation time and volume for the spheroids at day 20
- the Geltrex dilution (the paper says "according to the manufacturer's instructions")
- the cell number or density at which spheroids are considered ready

## Related protocols

08 coating, 09 spheroid migration, 13 compound exposure, 14 neurite imaging, 15 immunocytochemistry, 33 MTT assay, 34 DNAq assay.
