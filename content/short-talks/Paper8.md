---
title: "Short talk: Analysing multiplexed assays of variant effects with mutscan"
draft: false
type: "blog"
---

## Analysing multiplexed assays of variant effects with mutscan

Alexandra Bendel,Guillaume Diss,Charlotte Soneson,Michael B Stadler	

Friedrich Miescher Institute for Biomedical Research	

#### Abstract

Multiplex assays of variant effects (MAVE) measure the fitness of large numbers of sequence variants in a single experiment. For example, a large library of variants is created by mutating a sequence of interest (deep mutational scanning, DMS), and the resulting pool of variants is subjected to an assay that allows for amplification or selective enrichment of sequences with desirable properties. Such desirable variants are then identified by quantifying their abundance by sequencing before and after the selection. To provide a unified, flexible interface to analyse such experiments, we developed mutscan, an R package that covers the entire workflow, from FASTQ files to count table, statistical analysis and visualisation. The core read processing module is implemented in multi-threaded C++, which enables the analysis of large sequencing experiments with reasonable time and memory constraints. Various designs of experiments are supported by mutscan, for example single or paired reads with or without unique molecular identifiers (UMIs) and flexible composition of constant and variable sequence segments in any order. In order to find variants that either increase or decrease their relative abundance upon selection, mutscan employs the widely used and well-established statistical models provided in the edgeR and limma Bioconductor packages to perform statistical analysis. mutscan is currently available from https://github.com/fmicompbio/mutscan and is planned to be submitted to Bioconductor in this year.
