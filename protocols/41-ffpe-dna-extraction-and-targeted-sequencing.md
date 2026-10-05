# 41. DNA from FFPE tumour tissue, targeted sequencing and Sanger confirmation

| | |
|---|---|
| Version | 0.1, draft, October 2026 |
| Status | Reference method. The laboratory work was done at the partner centre in Moscow. Not planned for the Zosen Lab. |
| Source paper | Anoshkin et al. 2022, [doi:10.1016/j.heliyon.2022.e10291](https://doi.org/10.1016/j.heliyon.2022.e10291) |
| Role of the Zosen Lab PI | Second author. Took part in the data analysis. |
| Licence | CC BY 4.0 |

## Purpose

Describe how a tumour's actionable and driver mutations were found in FFPE DNA with Ion AmpliSeq panels on an Ion S5, then confirmed by Sanger sequencing.

## Before you start

The same ethics and consent conditions as in protocol 40 apply. The Supplementary Material of the paper holds the Sanger primers, the PCR parameters for the TERT promoter mutations (C250T and C228T), the MGMT methylation assay and the custom gene list. These were not available when this protocol was written, so they are listed as not stated.

## Materials (as in the paper)

- GeneRead DNA FFPE kit (Qiagen 180134).
- Ion AmpliSeq Comprehensive Cancer Panel (Thermo Fisher 4477685).
- Oncomine Tumor Mutation Load Assay (Thermo Fisher A37909).
- A custom panel of 25 genes involved in epigenetic regulation.
- Ion S5 System (Thermo Fisher).

## Procedure

1. Extract DNA from the FFPE tumour tissue with the GeneRead DNA FFPE kit.
2. Prepare the libraries by Ion AmpliSeq targeted amplification, using the three panels above.
3. Sequence on the Ion S5 System.
4. Analyse the data (protocol 43).
5. **Verify every point mutation found by Sanger sequencing.**
6. Test the TERT promoter hotspot mutations and the MGMT methylation status by the methods in the Supplementary Material.
7. Report the median read coverage per panel. For this case it was 870 (Comprehensive Cancer Panel), 619 (Oncomine TML) and 2081 (custom panel).

## Not stated in the paper

- DNA input, quality criteria and the number of cycles
- the library preparation kit versions and the sequencing chip
- the Sanger primer sequences (Supplementary Material)

## Related protocols

40 histopathology, 42 SNP-array, 43 variant filtering.
