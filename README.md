# RNA-seq Analysis of Dexamethasone-Treated Airway Cells

## Project Overview

This project investigates changes in gene expression following dexamethasone treatment in human airway smooth muscle cells using the publicly available `airway` dataset.

## Research Question

How does dexamethasone treatment affect gene expression in human airway smooth muscle cells?

## Methods

The analysis was performed in R using:

- DESeq2 for differential gene expression analysis, accounting for cell-line differences.
- ggplot2 for volcano plot visualization.
- Principal Component Analysis (PCA) for exploring sample variation.
- clusterProfiler for Gene Ontology enrichment analysis.

## Key Results

Using an adjusted p-value threshold of 0.05, 4,028 genes were identified as differentially expressed, including 2,211 upregulated and 1,817 downregulated genes.

GO enrichment identified 572 significantly enriched biological process terms, including angiogenesis and extracellular matrix organization.

## Reproducibility

The analysis code and explanations are available in `Airway_dataset.Rmd`. Software versions are recorded in `sessionInfo.txt`.