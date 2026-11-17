# DRAGEN joint-genotyping job wrappers

This directory is part of the GenomeIndia consortium code fork. The original [upstream repository](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes) is the source of the scripts. Read the original [pipeline notes](README.txt) and [WGS commands](WGS_pipeline_command.txt). These SLURM array wrappers call an external DRAGEN IGG runner. Match its version, run order, shard lists, scheduler settings and required study inputs before submitting jobs.

## Script and notebook guide

| File | Purpose |
| --- | --- |
| [`step1_igg.sh`](step1_igg.sh) | Dispatches stage 1 by batch and shard. |
| [`step2_igg.sh`](step2_igg.sh) | Dispatches stage 2 by version and shard. |
| [`step3_igg.sh`](step3_igg.sh) | Dispatches stage 3 by version, batch and shard. |
| [`step4_igg.sh`](step4_igg.sh) | Dispatches stage 4 by version, merge setting and shard. |
| [`step5_igg.sh`](step5_igg.sh) | Dispatches stage 5 by version, batch and chromosome. |
| [`step6_igg.sh`](step6_igg.sh) | Dispatches stage 6 by version, merge setting and chromosome. |

[Repository overview](../README.md)
