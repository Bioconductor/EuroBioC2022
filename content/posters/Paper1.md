---
title: "Poster: Introducing the hermes package for analyzing and reporting RNA-seq data"
draft: false
type: "blog"
---

## Introducing the hermes package for analyzing and reporting RNA-seq data
Daniel Sabanes Bove
Roche
#### Abstract

The hermes package published on Bioconductor provides classes and functions for quality control, filtering, normalization and differential expression analysis of pre-processed RNA-seq data. Data can be imported from `SummarizedExperiment` as well as `matrix` objects and can be annotated from BioMart. Filtering for genes without too low expression or containing required annotations, as well as filtering for samples with sufficient correlation to other samples or total number of reads is supported. The standard normalization methods including `cpm`, `rpkm` and `tpm` can be used, and `DESeq2` as well as `voom` differential expression analyses are available.  We present the package, as well as a (still closed but soon open source) extension including Shiny modules based on the "teal" framework.
