# 44. Statistics, replicate definitions, outliers and blinding

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | The practice described in the published papers, collected in one place. It is not a statistics course. Agree your analysis plan with a statistician before you collect data. |
| Source papers | Zosen et al. 2018, 2021, 2022, 2023. Labba et al. 2022. Kaplan-Arabaci et al. 2025. The spinal cord organoid paper (2026). See `docs/source-papers.md` for the references. |
| Role of the Zosen Lab PI | First or contributing author of the source papers (see each protocol). |
| Licence | CC BY 4.0 |

## Purpose

State what counts as one independent replicate, how the data were compared and which outlier rules were used, so that new members design experiments and report results in the same way.

## What counts as n

| Experiment | Independent unit | Source |
|---|---|---|
| Chicken embryo (histology, drug levels, western blot) | One embryo. Measurements from individual embryos are independent values. At least 3 animals per group in each of 3 independent experiments gave n ≥ 9 for histology. | AEDs 2022, Chick 2021 |
| Chicken CGN culture | A culture from a unique set of embryonic cerebella. | Paracetamol 2022 |
| NT2N culture | A culture that was differentiated separately and came from NTERA2 cells grown for at least 3 serial or parallel passages, with at least one month between independent cultures. | Paracetamol 2022 |
| Cell-line experiments | Replicates of n ≥ 3 to 6 per group (the papers do not define the unit further). | ADDs 2023, 2025 |
| Cell-culture experiments (CGN, NT2N) | Three repetitions per experiment, each an independent population, as defined in the two rows above. | Paracetamol 2022 |
| Organoids | Not defined in the paper (protocol 07 lists this as a gap). | SCOs 2026 |

Wells of one plate are technical replicates. Do not use them as n.

## Tests used in the papers

- Two groups: Student's t-test (normal data) or Mann-Whitney U test.
- Several groups against a control: one-way ANOVA with Dunnett's test. Kruskal-Wallis ANOVA on ranks with Dunn's test for data that fail normality, or with unequal group sizes.
- All pairs: one-way ANOVA with Tukey's test (2023) or Bonferroni (organoid paper, 2026).
- Time series (IncuCyte, live-cell): two-way ANOVA or repeated measures, using all time points. Dunnett's test for treatment versus control (2022).
- Significance: alpha 0.05. Asterisks: * p < 0.05, ** p < 0.01, *** p < 0.001, **** p < 0.0001.
- Report: mean ± SD (the 2018 paper uses SE, the organoid paper uses SEM, IncuCyte data in 2023 and 2025 use SEM). Say which in every figure legend.
- Software in the papers: GraphPad Prism 8 and later, SigmaStat 4.0, IBM SPSS 26.0 (reliability), OriginLab 8, and Python scripts.
- Normalise measurements to the average of the solvent controls before statistics (protocols 29 and 32).

## Outliers

- Grubbs' test was used in several papers. The alpha was 0.05 in most and **0.2** in the western blot data of the 2022 CGN paper. A rule fixed in advance is better than one chosen afterwards.
- Report every removed value and the reason. One or two outliers removed per dataset is what the papers report.
- The 2022 NT2N and CGN paper also excluded "SCC samples used in migration experiments" from the statistics "to avoid confounding bias in favour of treatment effect". What SCC stands for is not defined in the extract I used, so check the paper.

## Blinding and agreement between observers

1. Label samples without reference to treatment (A01, A02, A03 and so on), and give the scorer as little background as possible.
2. Two researchers score independently.
3. Calculate the interobserver agreement as an intraclass correlation coefficient (moderate 0.5 to 0.8, strong 0.8 to 1). If agreement is moderate, agree a consensus score.

## What to write down before the experiment

The unit of n, the primary outcome, the test, the outlier rule and who scores blinded. Put it in the lab notebook and the project folder (handbook chapter 8).

## Not stated in the papers

- power calculations
- how normality was tested, apart from "the normality test"
- the correction for multiple outcomes in one experiment

## Related protocols

Every protocol in this collection. In particular 23 blinded scoring, 29 and 32 normalisation.
