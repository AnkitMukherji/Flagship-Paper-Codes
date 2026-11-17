# Variant prioritization and ClinVar summaries

This directory is part of the GenomeIndia consortium code fork. The original [upstream repository](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes) is the source of the scripts. See the [original notes](README.txt) for the study files and workflow. Align reference coordinates, variant alleles, annotation release and frequency inputs before comparisons.

## Script and notebook guide

| File | Purpose |
| --- | --- |
| [`Clinvar.py`](Clinvar.py) | Filters and matches ClinVar records against cohort variant-frequency data and exports matched summaries. |
| [`pDMM_LoF_ACMG.py`](pDMM_LoF_ACMG.py) | Applies missense and loss-of-function filters, uses bcftools to extract selected genotypes and prepares follow-up summaries. |

[Repository overview](../README.md)
