# GenomeIndia figure scripts

This directory is part of the GenomeIndia consortium code fork. The original [upstream repository](https://github.com/genomeindiaconsortium/Flagship-Paper-Codes) is the source of the scripts. Each panel script reads a particular study summary table, workbook or analysis output. Check the input columns, packages, fonts and working directory for the script you choose.

## Script and notebook guide

| File | Purpose |
| --- | --- |
| [`Fig1b_barplot_novel.R`](Fig1b_barplot_novel.R) | Plots novel SNV and indel counts for the specified comparisons. |
| [`Fig1c_ridge_plot_autosomes.R`](Fig1c_ridge_plot_autosomes.R) | Draws population-level autosomal variant-summary ridgeline plots and a companion legend. |
| [`Fig1d_fst_jaccard_clean.R`](Fig1d_fst_jaccard_clean.R) | Draws population comparison heatmaps for weighted FST and Jaccard values. |
| [`Fig2e_mtDNA_vs_chrY.R`](Fig2e_mtDNA_vs_chrY.R) | Plots diversity summaries and compares mitochondrial and Y chromosome patterns. |
| [`Fig4d_final_plot_complex_heatmap.R`](Fig4d_final_plot_complex_heatmap.R) | Builds the pharmacogenomics frequency heatmap using the supplied study table. |
| [`Fig4ef_PGx_staralleles.R`](Fig4ef_PGx_staralleles.R) | Plots proportions of the inferred pharmacogenomic phenotypes used in panels 4e and 4f. |
| [`Fig5C_Plot.R`](Fig5C_Plot.R) | Plots imputation-quality summaries against minor allele frequency bins. |
| [`Fig5D_Plot.R`](Fig5D_Plot.R) | Plots overlap counts from the imputation-comparison workbook. |
| [`Fig5E_Plot.py`](Fig5E_Plot.py) | Visualizes per-variant evaluation metrics against imputation INFO. |
| [`Fig5_PRS.R`](Fig5_PRS.R) | Plots comparative polygenic score summaries from the supplied input table. |
| [`Figure_1B_barplot.R`](Figure_1B_barplot.R) | Draws SNV and indel novelty-status bar charts. |
| [`Figure_1D_Heatmap.py`](Figure_1D_Heatmap.py) | Plots the Figure1D workbook values as a group-level heatmap. |
| [`Figure_1E_plot.R`](Figure_1E_plot.R) | Builds Figure 1E curves from study workbook inputs and bootstrap calculations. |
| [`Sunburst_plot_fig4C.R`](Sunburst_plot_fig4C.R) | Builds the hierarchy for the Figure 4C Plotly sunburst. |
| [`sankey_plot_fig4B.py`](sankey_plot_fig4B.py) | Builds a Plotly Sankey chart of variant functional impact and medical relevance. Review the input expression before executing. |

[Repository overview](../README.md)
