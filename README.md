# colorectal-cancer-rnaseq-analysis
DESeq2 analysis of F. nucleatum-induced transcriptomic changes in colorectal cancer cell lines (HT-29, MDST8)

# Colorectal Cancer Microbiome-Host Transcriptomics

RNA-seq differential expression analysis investigating F. nucleatum-induced gene expression changes in colorectal cancer cell lines.

## Overview
- **Cell lines**: HT-29 (CMS1), MDST8 (CMS4)  
- **Treatment**: F. nucleatum infection vs control
- **Method**: DESeq2 differential expression analysis

## Key Findings
- **HT-29**: 18 significantly differentially expressed genes
- **MDST8**: 4 significantly differentially expressed genes  
- Results suggest CMS subtype influences host response to bacterial infection

## Technical Details
- Filtering: genes with <5 reads removed
- Significance: padj < 0.05, |log2FC| > 1
- Gene annotation via Ensembl

## Requirements
- R (≥4.0)
- DESeq2
- tidyverse
- edgeR
