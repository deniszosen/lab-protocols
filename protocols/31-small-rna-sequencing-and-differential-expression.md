# 31. Small RNA sequencing and differential expression analysis

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Written from a short published method. Library preparation and sequencing were done by a core facility. Not yet validated in the Zosen Lab. |
| Source paper | Kaplan-Arabaci et al. 2025, [doi:10.1016/j.neuint.2025.106056](https://doi.org/10.1016/j.neuint.2025.106056) |
| Role of the Zosen Lab PI | Second author. |
| Licence | CC BY 4.0 |

## Purpose

Profile microRNAs in embryonic chicken cerebellum after drug exposure, find the differentially expressed miRNAs and link them to their human counterparts.

## Before you start

Send RNA from protocol 30 to the sequencing facility with the sample sheet. Agree the minimum quality, quantity and volume with the facility. The 2025 study used the Norwegian Sequencing Center.

## Materials

- Library preparation: NEBNext Small RNA Library Prep Set for Illumina.
- Sequencer: Illumina NextSeq 500 (high-throughput sequencing).
- Reference: Gallus gallus miRNA sequences from miRBase (http://www.mirbase.org). Genome: Gallus gallus.
- Software: DESeq2, ggplot, the NCBI nucleotide BLAST tool, and miRGeneDB (http://mirgenedb.org).

## Procedure

1. Prepare small RNA libraries and sequence them (done by the facility). Receive the raw data as FASTQ files with nucleotide sequences and quality scores.
2. Align the reads to the Gallus gallus genome. Convert the results to SAM/BAM.
3. Count the reads for each sequence.
4. Test for changes in miRNA expression between samples with DESeq2. DESeq2 controls the false discovery rate and returns adjusted p-values (padj, Benjamini-Hochberg). The paper used a cutoff of padj < 0.1, meaning that fewer than 10% of the significant results are expected to be false positives (Love et al. 2015).
5. Draw volcano plots from the adjusted p-values. Make heatmaps and volcano plots with ggplot.
6. **Find the human counterparts.** For the miRNAs of interest, compare the chicken precursor sequences to human sequences with BLAST (NCBI nucleotide). In miRGeneDB, find the Gallus gallus precursor sequences and the corresponding human miRNAs, where they exist.
7. Search the literature for the functions of individual miRNAs and miRNA families.
8. Store the raw FASTQ files unchanged and read-only, and record the genome and annotation versions, the software versions and the random seeds (handbook, chapter 8).

## Not stated in the paper

- the read trimming, the aligner and its settings
- the number of reads per sample and the minimum count filter
- the software versions
- the design formula used in DESeq2

## Related protocols

30 RNA isolation, 32 qPCR validation, 44 statistics.
