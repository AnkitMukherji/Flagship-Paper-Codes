# GenomeIndia: Consortium Analysis Code

This repository is a **fork of [genomeindiaconsortium/Flagship-Paper-Codes](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes)**. It preserves consortium code for variant processing, annotation, imputation evaluation, pharmacogenomics, and paper figures.

Authorship belongs to the original contributors. Ankit Mukherjee's broader GenomeIndia contributions are described in the [research CV](https://github.com/AnkitMukherji/CV); hosting this fork does not imply sole authorship of the pipeline or every module.

## Navigate the methods

| Directory | Analysis role |
| --- | --- |
| [DRAGEN_pipeline/](DRAGEN_pipeline/) | Whole-genome processing commands and staged scripts |
| [Variant_annotation/](Variant_annotation/) | VEP and loss-of-function annotation |
| [pdMM_LoF_ACMG_Clinvar/](pdMM_LoF_ACMG_Clinvar/) | Missense/LoF prioritization and medically relevant annotation |
| [Imputation/](Imputation/) | Phasing, imputation, and evaluation metrics |
| [Pharmacogenomics/](Pharmacogenomics/) | Population/sample summaries, SNPs/indels, star alleles, and PGx figures |
| [Plotting_codes/](Plotting_codes/) | Scientific figure generation |

## Reproduction and interpretation

Start with the module-specific README files and inspect each script's required inputs. This is consortium analysis code with study-specific resources, paths, and software requirements; there is no single installation or complete automated reproduction command at the root.

Record the reference assembly, annotation releases, caller/filter settings, sample selection, and population definitions when reproducing any module. Variant prioritization and population enrichment nominate candidates; they do not independently establish pathogenicity or clinical actionability.

Related personal analysis repository: [Medical_Relevance_GI](https://github.com/AnkitMukherji/Medical_Relevance_GI).

## Original consortium resource notes

**GenomeIndia**

This repository corresponds to the codes used for calling and analysis of variants for the GenomeIndia flagship paper.


Reference genome - https://drive.google.com/drive/folders/11TCIk4XEgbzg5j9GRe_vvzaDEc1zFD11?usp=drive_link

Frequency of small variants - https://drive.google.com/drive/folders/1hvPIDETkw9WVJEQjUW3vTffUBQTbdnK1?usp=sharing

Clinvar file used for annotation- https://drive.google.com/file/d/1d1Wmwl1UqEhm_L7aI20JQCOVIlUFYUt5/view?usp=sharing
