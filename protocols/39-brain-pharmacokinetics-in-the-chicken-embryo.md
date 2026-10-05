# 39. Brain pharmacokinetics in the chicken embryo

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from two published methods. Not yet validated in the Zosen Lab. |
| Source papers | Zosen et al. 2021, [doi:10.1016/j.vascn.2021.107105](https://doi.org/10.1016/j.vascn.2021.107105). Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) |
| Role of the Zosen Lab PI | First author (2021). Second author (2025). |
| Licence | CC BY 4.0 |

## Purpose

Plan a time-course of brain drug concentrations after one injection into the allantoic sac, and turn the measured concentrations into the parameters that let you choose a dose and time point for later experiments. The aim is to expose the brain to concentrations in a clinically relevant range.

## Before you start

- The animal permit (FOTS 13896) belongs to the original study. From embryonic day 14 (E14) the chicken embryo is an animal under EU Directive 2010/63/EU. You need your own approval, and the eggs must stay under the sampling scheme of that approval.
- Do the injection and tissue collection as in protocols 10 and 11. The drug assays are protocols 36 to 38.

## Design from the two papers

| Item | 2021 paper (VPA, LTG) | 2025 paper (escitalopram, venlafaxine) |
|---|---|---|
| Strain | Ross 308 broiler | Ross 308 broiler |
| Injection day | E13 or E16 | E13 or E16 |
| Route and volume | Allantoic sac, 1 µL/g egg | Allantoic sac, 1 µL/g egg, 29-gauge needle |
| Stock | 100 mM VPA (16.6 mg/mL) or 5 mM LTG (1.9 mg/mL) | 0.3 mM escitalopram (0.1 mg/kg) or 1.27 mM venlafaxine (0.35 mg/kg) in 0.9% NaCl |
| Control | Saline | Saline |
| Time points | 5, 15, 30 min; 1, 2, 4, 6, 12, 24 h | 0.25, 0.5, 1, 2, 3, 4, 5, 6, 7, 8, 12, 18, 24, 48, 72 h |
| Tissue | Whole brain | Whole brain or cerebellum (and E17 samples) |
| Replicates | n = 3 per time point | n = 3 to 6 |

## Procedure

1. Candle (transilluminate) the egg to find a site free of large vessels, and confirm the embryo is alive.
2. Inject the dose into the allantoic sac with a fine needle. Inject saline into control eggs.
3. At each time point, anaesthetise by hypothermia (egg submerged in crushed ice for 7 minutes), then decapitate. For the 5-minute point, the 2021 paper counts the cooling time as part of the exposure time.
4. Open the skull, remove the cranium, detach the whole brain, and remove the meninges with forceps.
5. Freeze in liquid nitrogen and store at −80 °C (protocol 11).
6. Quantify the drug (protocols 36 to 38).
7. Treat the measurement from one embryo as one independent value.
8. Plot brain concentration against time. Calculate:
   - area under the curve (AUC) by the trapezoidal rule
   - the maximum brain concentration (Cmax) and the time to reach it (Tmax)
   - the elimination constant (Ke), calculated from the slope of the last 3 to 4 concentration-time points (2021 paper)
9. Compare the measured brain concentrations with human therapeutic serum or brain data to judge whether the dose is clinically relevant.
10. Statistics: Wilcoxon test or one-way ANOVA, p < 0.05, mean ± SD. Remove outliers by Grubbs' method (alpha 0.05) and report each removal (protocol 44).

## What the 2021 paper found (for planning)

Both drugs reached the brain within 5 to 15 minutes. As a share of the injected concentration (assuming even distribution through the egg), the peak brain concentration was 28% for VPA (Tmax 4 h) and 36% for LTG (Tmax 2 h) after E13 injection. After E16 injection it was 39% for VPA (Tmax 0.5 h) and 12% for LTG (Tmax 1 h). So the injection day changes the result: more VPA and less LTG reached the brain at E16. After the VPA peak at E13 the concentration stayed at about 80% of the peak, whereas at E16 it fell mono-exponentially to 30%. Higher doses given at E16 (VPA 83 and 166 mg/kg, LTG 3.8 and 9.6 mg/kg) gave proportionally higher brain concentrations. After 72 hours, 4% (VPA) and 6% (LTG) of the injected dose was still in the brain.

## Not stated in the papers

- the software or code for the elimination fit, beyond GraphPad Prism 8
- the exact fitting model beyond the slope of the last 3 to 4 points

## Related protocols

10 in-ovo exposure, 11 sample collection, 36 to 38 drug assays, 44 statistics.
