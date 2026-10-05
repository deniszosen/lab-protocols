# 29. Plasmid transfection and dual-luciferase reporter assay in neuronal cultures

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Collected from three papers with three cell types. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2023, [doi:10.1016/j.neuint.2023.105571](https://doi.org/10.1016/j.neuint.2023.105571). Zosen et al. 2022, [doi:10.1016/j.ntt.2021.107057](https://doi.org/10.1016/j.ntt.2021.107057). Yadav et al. 2021, [doi:10.1016/j.toxlet.2020.12.007](https://doi.org/10.1016/j.toxlet.2020.12.007). The methods follow Strøm et al. 2010, cited in the papers. |
| Role of the Zosen Lab PI | First author (2023, 2022). Contributing author (2021). |
| Licence | CC BY 4.0 |

## Purpose

Measure how a compound changes the activity of a promoter, by transfecting a firefly luciferase reporter driven by that promoter together with a Renilla luciferase control, and reading both signals.

## Before you start

- Work with plasmids under the biosafety rules for your institution. Record the plasmid name, the source and the lot.
- The firefly plasmids in the papers were gifts from collaborators: pGL4.15 BDNF pIV (−204/+320) from Prof. Tõnis Timmusk (Pruunsild et al. 2011), the PAX6-P1 plasmid pWT-P1 (Austdal et al. 2016; Zheng et al. 2001), and the GCLC promoter plasmid from R. Blomhoff. Request the plasmid with a material transfer agreement.

## Materials

- K2 Transfection System (Biontex T060-0.75) for SH-SY5Y neurons. K2 multiplier reagent (Biontex T050-2.0) for CGNs.
- Control plasmid: pRL-CMV (Promega E2261) for SH-SY5Y, or pRL-TK (Promega) for CGNs and PC12.
- D-luciferin (Thermo 88291). Dual-Luciferase Reporter Assay System (Promega E1910).
- A luminometer (EG&G Berthold Lumat LB9507) or a CLARIOstar plate reader (BMG Labtech).

## Procedure

Use 0.8 µg of the firefly plasmid and 0.2 µg of the Renilla plasmid, to a total of **1 µg DNA per mL of culture medium**, in all three variants. The PC12 paper (2021) prints these as "0.8 mg", "0.2 mg" and "1 mg DNA/mL". The same text layer prints µ as m elsewhere, so this is most likely a unit artefact, and the 2022 and 2023 papers give µg. Confirm with the authors before relying on it.

### Variant A: SH-SY5Y neurons (BDNF promoter IV, 2023)

1. On DIV 17, plate differentiating neurons in 6-well plates (Eppendorf 0030720113) at 7 × 10^5 cells per well.
2. On DIV 18, transfect with the K2 system according to the manufacturer's recommendations. Incubate overnight at 37 °C and 5% CO2.
3. On DIV 19, expose the cells to the test compounds in fresh differentiation medium.
4. After 48 hours (DIV 21), measure firefly luciferase with D-luciferin and Renilla luciferase with the Dual-Luciferase kit, in the luminometer.
5. Calculate the firefly/Renilla ratio and present it relative to the average of the controls.

### Variant B: chicken CGNs (PAX6-P1 promoter, 2022)

1. At DIV 2, incubate CGNs for 2 hours with 10 µL/mL of K2 multiplier reagent.
2. Prepare the transfection solution by mixing a plasmid solution with a K2 solution. Incubate the cells with it for 5 to 6 hours at 37 °C and 5% CO2.
3. Expose to valproate (100, 500 or 1000 µM) or lamotrigine (1, 10 or 100 µM) in fresh medium.
4. After 48 hours, measure firefly luciferase with D-luciferin in the Lumat LB9507, and Renilla luciferase with the Dual-Luciferase kit on a CLARIOstar plate reader.
5. Calculate the PAX6-P1/Renilla ratio and normalise to the average of the controls.

### Variant C: PC12 cells (GCLC promoter, 2021)

1. Seed cells in 35 mm dishes at 1.25 × 10^4 cells/cm² and allow them to attach for 24 hours.
2. On culture day 1, transfect with the GCLC-luciferase plasmid (GCLC catalytic subunit promoter) and pRL-TK, following Sørvik et al. 2018. Replace the transfection medium with fresh medium after 4 hours.
3. On culture day 2, expose the cells to the test compounds in serum-free medium or serum-free medium with NGF.
4. After 48 hours, measure firefly luciferase in the Lumat LB9507 and Renilla luciferase with the Dual-Luciferase kit.

## Not stated in the papers

- the volumes of K2 reagent and the DNA-to-reagent ratio (the papers refer to the manufacturer's instructions)
- the luminometer integration time and the volumes of lysis buffer and substrate
- the minimum Renilla signal for accepting a well

## Related protocols

01 SH-SY5Y, 03 PC12, 04 CGNs, 13 compound exposure, 44 statistics.
