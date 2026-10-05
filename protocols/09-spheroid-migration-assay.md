# 09. Spheroid migration assay with CGN and NT2N spheroids

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. The ImageJ macro is in the paper's supplement (Table S2) and is not reproduced here. Not yet validated in the Zosen Lab. |
| Source paper | Labba et al. 2022, [doi:10.1016/j.taap.2022.116130](https://doi.org/10.1016/j.taap.2022.116130) |
| Role of the Zosen Lab PI | Contributing author. |
| Licence | CC BY 4.0 |

## Purpose

Measure how cells migrate radially out of spheroids under a treatment, and separate migration from proliferation by including dissociated single-cell controls in every experiment.

## Before you start

- Chicken CGN spheroids need an approved animal project (see protocol 04). NT2N spheroids start from the culture in protocol 02.
- Treat human-derived cells as potentially infectious.

## Materials

- CGN single-cell suspension at DIV 0 (protocol 04), or NT2N cells differentiated for 20 days (protocol 02).
- 100 mm low-adhesion dishes. Orbital rotator for NT2N spheroids.
- TPP 96-well plates (Sigma Z707910), coated as in protocol 08: PLL for CGN spheroids, PLL and fibronectin for NT2N spheroids.
- Serum-containing medium for CGNs (protocol 04). For NT2Ns, a 1:1 mixture of conditioned and fresh defined medium, where the fresh half has 10 µM RA.
- Treatment medium: defined medium with AraC for CGNs (protocol 04). Defined medium for NT2Ns. Test compound added (protocol 13).
- IncuCyte ZOOM (CGNs) or IncuCyte S3 (NT2Ns), and ImageJ.

## Procedure

### CGN spheroids

1. Transfer 20 mL of serum-containing medium with the DIV 0 single-cell suspension at 2 × 10^6 cells/mL into 100 mm low-adhesion dishes. Incubate overnight at 37 °C and 5% CO2.
2. The next day, dislodge and dissociate the clusters by triturating very gently 3 to 5 times with a 25 mL serological pipette.
3. Centrifuge the spheroids at 200 RCF for 30 seconds. Resuspend in 5 mL serum-containing medium and centrifuge again with the same settings.
4. After both spins, keep the supernatants. They contain single cells and become the **single-cell control (SCC)**.
5. Seed the spheroids at 1500 spheroids/cm² in serum-containing medium into PLL-coated TPP 96-well plates.
6. Incubate for 4 hours at 37 °C and 5% CO2. Then replace the serum-containing medium with defined medium containing AraC and the treatment.

### NT2N spheroids

1. Re-seed 10 mL of NT2N suspension at 5 × 10^5 cells/mL into 100 mm low-adhesion dishes. Incubate overnight at 37 °C and 5% CO2 on a rotator.
2. Harvest and count the spheroids in the same way as for the CGN spheroids (steps 2 to 4 above).
3. Seed into PLL- and fibronectin-coated TPP 96-well plates in the 1:1 conditioned/fresh defined medium (fresh half with 10 µM RA).
4. Incubate for 4 hours. Then replace the medium with fresh 1:1 conditioned/fresh medium that contains the treatment.

### Imaging and analysis

5. Image the plates by time-lapse phase contrast. The study took 4 images per well at 10× every 90 minutes for 72 hours (IncuCyte ZOOM for CGNs, IncuCyte S3 for NT2Ns, at 37 °C and 5% CO2).
6. Quantify the growth area covered by cells that migrated radially from the spheroids, using ImageJ image processing and its particle analysis function (macro in Table S2 of the paper).
7. Use 12 wells per treatment, with four images per well per time point.
8. Include SCC wells in every experiment. Do not include them in the statistics: the study excluded them to avoid bias in favour of the treatment effect.

## Quality checks

- General practice, not from the paper: spheroids of similar size across wells at seeding.
- From the paper: SCC wells present in every plate.
- Three independent populations as defined in protocols 02 and 04.

## Not stated in the paper

- the spheroid size range and how spheroids are counted
- the exact ImageJ settings, which are in the supplement

## Related protocols

02 NT2N, 04 CGNs, 08 coating, 13 compound exposure, 14 live imaging.
