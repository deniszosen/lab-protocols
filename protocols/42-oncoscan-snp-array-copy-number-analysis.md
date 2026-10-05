# 42. OncoScan SNP-array for chromosomal and copy-number analysis

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Reference method. The array work was done at the partner centre in Moscow. Not planned for the Zosen Lab. |
| Source paper | Anoshkin et al. 2022, [doi:10.1016/j.heliyon.2022.e10291](https://doi.org/10.1016/j.heliyon.2022.e10291) |
| Role of the Zosen Lab PI | Second author. Took part in the data analysis. |
| Licence | CC BY 4.0 |

## Purpose

Detect chromosomal aberrations and copy-number changes in FFPE tumour DNA with the OncoScan SNP-array, and review them by hand.

## Before you start

The same ethics and consent conditions as in protocol 40 apply.

## Materials (as in the paper)

- OncoScan (Thermo Fisher 902695).
- GeneChip Scanner 3000 7G System (Applied Biosystems 00-0213).
- Chromosome Analysis Suite (ChAS) 4.2 (Affymetrix) with the OncoScan default settings.

## Procedure

1. Run the array following the manufacturer's recommendations (the paper gives no further detail).
2. Analyse the data in ChAS 4.2 with the OncoScan default settings.
3. **Review every copy-number alteration manually.**
4. For pathway analysis, use the copy-number data. Exclude oncogenes that fall in loss regions and tumour suppressor genes that fall in gain regions. Run the enrichment with the ClusterProfiler R package, version 3.18.1 (protocol 43).

## Not stated in the paper

- DNA input and the thresholds for calling gains, losses and loss of heterozygosity
- the quality control metrics

## Related protocols

41 sequencing, 43 variant filtering and enrichment.
