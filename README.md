## human-TLS

Repository for analysis of mesoderm diversification in human iPSC-derived trunk-like structures.

## Overview

This repository contains analysis scripts used for single-nucleus RNA-seq, bulk RNA-seq, and ATAC-seq data in the context of human trunk-like structures (hTLS).

### Repository structure

`hTLS_snRNA-seq/`  
Single-nucleus RNA-seq analysis of hTLS datasets (Seurat workflows, UMAP visualisation, cluster annotation, trajectory analysis).

`TBX6_RNA-seq/`  
Bulk RNA-seq analysis of acute doxycycline-inducible TBX6 overexpression during early hTLS differentiation (DESeq2, PCA, volcano plots, GSEA, integration with reference datasets).

`dCas9_TBX6_D2_RNA-seq/`  
Bulk RNA-seq analysis of acute CRISPRi-mediated endogenous TBX6 knockdown, with samples harvested at day 2 of hTLS differentiation.

`dCas9_TBX6_timed_D5_RNA-seq/`  
Bulk RNA-seq analysis of timed CRISPRi-mediated endogenous TBX6 knockdown, comparing different temporal windows of TBX6 activity at day 5 of hTLS differentiation.

`dCas9_F1F2_RNA-seq/`  
Bulk RNA-seq analysis of CRISPRi FOXC1/2 perturbation experiments (DESeq2, marker analysis, GSEA, gene expression visualisation).

`early somite ATAC motif analysis/`  
Motif enrichment analysis of early somite ATAC-seq peaks using HOMER and bedtools.

### Requirements

R packages:
- Seurat
- ggplot2
- dplyr
- tidyr
- DESeq2
- clusterProfiler
- enrichplot
- pheatmap
- biomaRt
- emmeans
- ggpubr
- patchwork

External tools (ATAC analysis):
- bedtools
- HOMER

### Data

Input datasets generated in this study are available for download from the GEO database, with accession numbers:

`hTLS_snRNA-seq/` — available soon

`TBX6_RNA-seq/` — available soon

`dCas9_TBX6_D2_RNA-seq/` — available soon

`dCas9_TBX6_timed_D5_RNA-seq/` — available soon

`dCas9_F1F2_RNA-seq/` — available soon

Scripts expect locally stored data (e.g. count tables, metadata and reference datasets), and file paths will need to be updated accordingly.

### Notes

Scripts are provided as analysis workflows used for figure generation.

Paths are currently hard-coded and should be adapted before use.

This repository is not a packaged pipeline.

### Contact

For questions, please open an issue.
