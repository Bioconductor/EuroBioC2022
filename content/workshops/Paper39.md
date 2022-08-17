---
title: "Workshop: Single-cell multi-modal data handling in R/Bioconductor"
draft: false
type: "blog"
---

## Single-cell multi-modal data handling in R/Bioconductor
Dario Righelli,Davide Risso
Department of Statistical Sciences, University of Padova	

#### Abstract

Single-cell multi-modal experiments are becoming more common for investigating the roles of biological mechanisms involved in disease and in drug treatments. In the last few years, multiple multi-modal single-cell technologies have emerged, such as 10x-Genomics Multiome. These technologies allow to investigate gene expression (scRNAseq) together with chromatin accessibility (scATACseq), methylation, cell surface protein expression, and more. Despite computational methodologies for the analysis and the integration of these data are becoming standard, there is still a lack of a unified approach within Bioconductor for the loading, handling and processing of these data. For example, there are no readily available user-friendly functions for tasks such as the creation of genome browser tracks or pseudo-bulk samples from single-cell data. Here we present multimodaltools, an R package for the handling and manipulation of multi-modal single-cell data, initially focused on data from the 10X Genomics Multiome protocol (scATACseq+scRNAseq). We illustrate a workflow that, starting from the output of Cell Ranger, imports the data into a SingleCellExperiment object, using the main and altExp assays. We will show how to handle multiple samples, how to annotate data with singleR, build pseudo-bulk counts for scRNAseq with scuttle and for scATACseq with DEScan2. Additionally, we’ll use the annotation on the scRNAseq data to build genome browser tracks for the scRNAseq and scATACseq by using the sinto software, bedTools and DEScan2.
