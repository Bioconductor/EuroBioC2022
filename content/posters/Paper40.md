---
title: "Poster: Differential analysis of labelled MS-based proteomics data with msqrob2"
draft: false
type: "blog"
---

## Differential analysis of labelled MS-based proteomics data with msqrob2

Stijn Vandenbulcke

Universiteit Gent

#### Abstract

Mass spectrometry (MS) enables direct and comprehensive quantification of the proteome in biological samples, gaining a better understanding of biological systems. The quantification of the protein abundances can be done either with label-free workflows or by labelling with TMT or iTRAQ, which allows users to effectively multiplex multiple samples in the same MS-run.    We have adapted msqrob2, an R/Bioconductor tool for differential analysis of label-free MS-based proteomics data, towards the analysis of  labelled MS-based proteomics data. Existing tools for modelling labelled data, however, are limited to a specific data analysis workflow with pre-specified normalisation, summarisation and statistical inference steps. With msqrob2 the data analysis workflow becomes modular, and users can build a customized data analysis workflow. By building on the infrastructure provided by the QFeatures R/Bioconductor package, the original data and the output of each pre-processing step are stored in the same R object, which can be used for downstream analysis and visualisation.    We have performed a comprehensive benchmarking of many data analysis workflows, evaluating different normalisation and summarisation methods, comparing statistical inference with conventional linear and mixed models starting from data at the spectrum or protein level, and assessing the impact of imputation, empirical Bayes variance estimation, robust and ridge regression.
