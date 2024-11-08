# Data Analysis 

This repository contains a collection of R Markdown files for performing various data analysis tasks, primarily bulk RNA sequencing and proteomics.

## Table of Contents

- [Files](#files)
- [Installation](#installation)


## Files

1. **Data preparation_Bulk RNAseq.rmd**: Prepares and cleans bulk RNA sequencing data for downstream analysis.
2. **Venn diagram.rmd**: Generates Venn diagrams to visualize the overlap between multiple data sets.
3. **Volcano plot.rmd**: Creates volcano plots for visualizing differential expression analysis results.
4. **heatmap.rmd**: Constructs heatmaps to display patterns and clustering within gene expression or proteomic data.
5. **proteomic analysis.Rmd**: Analyzes proteomic data, including normalization and differential protein expression.

## Installation

To run these files, you will need to have R and RStudio installed. The following R packages are required:

```r
install.packages(c("DESeq2", "ggplot2", "tidyverse", "ggrepel", "RColorBrewer", 
                   "rlang", "pheatmap", "cowplot", "viridis", "ComplexHeatmap",
                   "shiny", "circlize", "EnhancedVolcano"))
