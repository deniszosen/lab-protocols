# 43. Variant filtering, tumour mutation burden and pathway enrichment

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a published method. Not yet validated in the Zosen Lab. This is the part of the clinical genomics workflow that can be reproduced as analysis. |
| Source paper | Anoshkin et al. 2022, [doi:10.1016/j.heliyon.2022.e10291](https://doi.org/10.1016/j.heliyon.2022.e10291) |
| Role of the Zosen Lab PI | Second author. Took part in the data analysis. |
| Licence | CC BY 4.0 |

## Purpose

Turn raw sequencing and array output into a short, reviewed list of pathogenic variants, a tumour mutation burden (TMB) value and a pathway enrichment.

## Before you start

Patient-derived data are personal data. Work only with data you have a legal basis to use, on a secure server, and follow protocol handling in handbook chapter 8.

## Materials (as in the paper)

- Torrent Suite 5.10.1 for the sequencing workflow.
- ANNOVAR for annotation. gnomAD for population frequency.
- Integrative Genomics Viewer (IGV) for manual review.
- Ion Reporter with the Oncomine Tumor Mutation Load Assay for TMB.
- R with the ClusterProfiler package, version 3.18.1.

## Procedure

1. Run the sequencing analysis in Torrent Suite 5.10.1.
2. Annotate the variants with ANNOVAR.
3. **Filter pathogenic mutations** with these parameters from the paper: read depth 250 (printed without a sign, and probably a minimum), variant allele fraction above 5%, strand bias excluded, and occurrence in the population below 1% (gnomAD).
4. Review **every** filtered point mutation by hand in IGV.
5. Confirm the retained mutations by Sanger sequencing (protocol 41).
6. Determine TMB with the Oncomine Tumor Mutation Load Assay panel in Ion Reporter. For the case in the paper, TMB was 0.85 mutations per Mb.
7. For pathway enrichment, take the copy-number results (protocol 42), drop oncogenes in loss regions and tumour suppressor genes in gain regions, and run ClusterProfiler.
8. Record every software version, the reference genome version and the command or settings, so that someone else can repeat the analysis (handbook chapter 8).

## Not stated in the paper

- the reference genome and database versions
- the gene sets and the multiple-testing threshold for the enrichment
- whether "read depth 250" is a minimum

## Related protocols

41 sequencing, 42 SNP-array, 44 statistics.
