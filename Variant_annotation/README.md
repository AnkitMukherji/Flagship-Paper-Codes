# VEP and loss-of-function annotation

This directory is part of the GenomeIndia consortium code fork. The original [upstream repository](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes) is the source of the scripts. See the [original VEP notes](README_VEP_LoF.txt) for required inputs. Check VEP configuration and the VCF header-handling code. Use a working copy of inputs for stages that rewrite headers.

## Script and notebook guide

| File | Purpose |
| --- | --- |
| [`S8_VEP_annotation_LoF_final_Sauma.py`](S8_VEP_annotation_LoF_final_Sauma.py) | Prepares VCF headers, invokes the configured VEP annotation process and handles resulting loss-of-function annotation. |

[Repository overview](../README.md)
