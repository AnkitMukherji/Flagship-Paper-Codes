# Phasing, imputation and evaluation

This directory is part of the GenomeIndia consortium code fork. The original [upstream repository](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes) is the source of the scripts. Inspect reference panel inputs, GRCh38 maps, sample and variant concordance, MPI configuration, path settings and software versions. Prepare phased genotypes before imputing and compare results against matching observed genotypes before aggregating metrics.

## Script and notebook guide

| File | Purpose |
| --- | --- |
| [`S15_1_Phasing.py`](S15_1_Phasing.py) | Uses MPI to distribute SHAPEIT phasing tasks and writes phased VCF outputs with bcftools. |
| [`S15_2_Imputation.py`](S15_2_Imputation.py) | Splits regions with the IMPUTE5 chunker, imputes each chunk, then concatenates, sorts, indexes and annotates the VCFs. |
| [`S15_3_0_Sensitivity_Specificity_Raw.py`](S15_3_0_Sensitivity_Specificity_Raw.py) | Compares overlapping imputed and observed WGS calls by chunk and writes raw metric components. |
| [`S15_3_1_Sensitivity_Specificity_Sum_Chunks.py`](S15_3_1_Sensitivity_Specificity_Sum_Chunks.py) | Aggregates raw per-variant metric components across evaluation chunks. |
| [`S15_3_2_Sensitivity_Specificity_finalMetrics.py`](S15_3_2_Sensitivity_Specificity_finalMetrics.py) | Combines summary inputs and computes final evaluation metrics. |

[Repository overview](../README.md)
