---
title: "Workshop: benchdamic: benchmarking of differential abundance methods for microbiome data"
draft: false
type: "blog"
---

## benchdamic: benchmarking of differential abundance methods for microbiome data
Matteo Calgaro,Chiara Romualdi,Davide Risso,Nicola Vitulo
University of Verona
#### Abstract

Recently, an increasing amount of methodological approaches have been proposed to tackle the complexity of metagenomics and microbiome data. In this scenario, reproducibility and replicability have become two critical issues, and the development of computational frameworks for the comparative evaluations of such methods is of utmost importance. Here, we present benchdamic, a Bioconductor package to benchmark methods for the identification of differentially abundant taxa. The structure of benchdamic can be summarized into 4 main parts. Each section is developed to answer specific questions when comparing samples from two experimental groups, namely: i) the ability for a given statistical distribution to successfully fit the input data, with particular focus on sparsity and their count nature; ii) the ability of the DA methods to control the type I error; iii) the concordance among methods; and iv) the accuracy of the findings based on a priori biological knowledge. benchdamic builds on existing R/Bioconductor infrastructure packages: the primary input of benchdamic’s main functions is a phyloseq object; however, for some functions a count table can also be used. Ready-to-use normalization and DA methods included in benchdamic are based on the edgeR, DESeq2, limma-voom, metagenomeSeq, ALDEx2, corncob, MAST, Seurat, and zinbwave packages. We envision two main uses of our package: (i) for practitioners interested in performing DA analysis on a new dataset, benchdamic can be used to identify the best DA methods among those already in the literature; (ii) for method developers interested in benchmarking their new approach, benchdamic can be used as an impartial tool to evaluate the relative merits of the new method compared to what is already available. The future of benchdamic is oriented to the addition of new aspects of analysis, e.g., new normalization methods and new DA approaches, to make it an always up-to-date tool including the most recent methods. benchdamic is available as an open-source package through the Bioconductor project. The package includes a vignette with a detailed tutorial.


