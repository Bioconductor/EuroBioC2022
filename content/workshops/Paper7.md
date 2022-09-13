---
title: "Workshop: Single-cell based spatial analysis and visualization of highly multiplexed imaging data"
draft: false
type: "blog"
---

## Single-cell based spatial analysis and visualization of highly multiplexed imaging data

Nils Eling,Jonas Windhager

University of Zurich

#### Abstract

Highly multiplexed imaging similarly to FISH-based spatial transcriptomics allows the detection of tens of biomolecules in single cells across tissue sections. Upon image processing and segmentation, the protein/RNA expression as well as the location and morphological features of individual cells are extracted for downstream analysis. We developed the steinbock framework to support image pre-processing, segmentation, feature extraction, and data export in a reproducible fashion. Single-cell, spatial data analysis and visualization are facilitated by the R/Bioconductor packages imcRtools and cytomapper. The imcRtools package allows the construction of spatial object graphs in which nodes represent cells and edges indicate cells in close physical proximity. The package further supports the visualization of these graphs together with the location of cells across multiple images. Spatial cellular neighborhoods can be detected by aggregating the phenotypes or expression across neighboring cells and using this information for cell clustering. A supervised spatial clustering approach is provided by detecting fully connected cells of the same phenotype prior to polygon expansion. The imcRtools package allows testing for enriched cell type/cell type interactions or avoidance by permuting cell labels per image. Finally, the cytomapper package allows the visualization of detected cell types or spatial communities directly on segmentation mask together with protein/marker expression. Together, the tools described here specifically support the spatial analysis and visualization of single-cell data. By using standardized data classes, the packages integrate into single-cell analysis workflows within the Bioconductor framework.
