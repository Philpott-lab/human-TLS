## human-TLS

Repository for analysis of mesoderm diversification in human iPSC-derived trunk-like structures.

## Overview

This repository contains analysis scripts used for single-nucleus RNA-seq, bulk RNA-seq, and ATAC-seq data in the context of human trunk-like structures (hTLS).

### Repository structure

`hTLS_snRNA-seq/`
Single-nucleus RNA-seq analysis of hTLS datasets (Seurat workflows, UMAP visualisation, cluster annotation).

`TBX6_RNA-seq/`
Bulk RNA-seq analysis of doxycycline-inducible TBX6 experiments (DESeq2, PCA, volcano plots, GSEA, integration with reference datasets).

`dCas9_F1F2_RNA-seq/`
Bulk RNA-seq analysis of CRISPRi FOXC1/2 perturbation experiments (DESeq2, marker analysis, GSEA, gene expression visualisation).

`early somite ATAC motif analysis/`
Motif enrichment analysis of early somite ATAC-seq peaks using HOMER and bedtools.

### Requirements

R packages:
  Seurat
  ggplot2
  dplyr
  DESeq2
  clusterProfiler
  enrichplot
  pheatmap
  biomaRt

External tools (ATAC analysis):
  bedtools
  HOMER

### Data

Input datasets generated in this study are available for download from GEO database, with accession numbers:

`hTLS_snRNA-seq/` (available soon)

`TBX6_RNA-seq/` GSE326087

`dCas9_F1F2_RNA-seq/` (available soon)

Scripts expect locally stored data (e.g. count tables, metadata and reference datasets), and file paths will need to be updated accordingly.

### Notes
Scripts are provided as analysis workflows used for figure generation.
Paths are currently hard-coded and should be adapted before use.
This repository is not a packaged pipeline.

### Contact

For questions, please open an issue.
