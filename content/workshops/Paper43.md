---
title: "Workshop: Differential abundance analysis for label-free mass spectrometry-based proteomics"
draft: false
type: "blog"
---

## Differential abundance analysis for label-free mass spectrometry-based proteomics

Laurent Gatto,Stijn Vandenbulcke,Nina Demeulemeester,Lieven Clement	

de Duve Institute, UCLouvain, Belgium

#### Abstract

Mass spectrometry (MS) based proteomics experiments generate ever larger datasets and, as a consequence, complex data interpretation challenges. This hands-on package demo focuses on the key concepts for differential analysis of MS-based proteomics data acquired via label free data dependent technologies. Moreover, examples involving more advanced experimental designs and blocking will also be introduced. In the workshop we will build upon the R/Bioconductor packages `QFeatures` and `msqrob2`. `QFeatures` provides infrastructure to manage and process proteomics data at the PSM, peptides and protein levels. It's unique feature is how it consistently links and handles these different assay levels. `msqrob2` provides a robust linear mixed model framework for assessing differential abundance in MS-based quantitative proteomics experiments. Its workflows can start from raw peptide intensities or summarised protein expression values. The model parameter estimates can be stabilized by ridge regression, empirical Bayes variance estimation and robust M-estimation. `msqrob2` builds on `QFeature` infrastructure to store the model results together with the raw and preprocessed data. ## Pre-requisites
- Basic knowledge of R syntax
- Being familiar with linear modelling
- Familiarity with Bioconductor data infrastructure such as SummarizedExperiment would be beneficial. 

## Background reading 

- The `QFeatures` vignettes: https://rformassspectrometry.github.io/QFeatures/articles/QFeatures.html 
- The PDA website https://statomics.github.io/PDA/ is a good reference for differential abundance analysis of label free proteomics data with R/Bioconductor 
- `msqrob2` paper: https://biblio.ugent.be/publication/8671260/file/8671927.pdf ## Workshop goals and objectives 
- Participants will learn how to use `QFeatures` and `msqrob2`.
- To import mass spectrometry-based proteomics data in R.
- To perform the key pre-processing steps: log transformation, filtering, normalisation and summarisation.
- To understand the differences in performance of popular strategies to summarise peptide level data in protein expression values.
- To build models for the downstream differential abundance analysis at the protein level.
- To translate the research hypothesis in the correct contrast (linear combination of the model parameters) when assessing experiments with more complex designs.
- To build upon the `QFeatures` infrastructure for data visualisation of the differentially abundant proteins.
