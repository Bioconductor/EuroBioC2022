---
title: "Workshop: Inference and Analysis of Synteny Networks with syntenet"
draft: false
type: "blog"
---

## Inference and Analysis of Synteny Networks with syntenet

Fabrício Almeida-Silva,Kristian K Ullrich,Tao Zhao,Yves Van de Peer	

FA-S and YVdP: VIB-UGent Center for Plant Systems Biology, Ghent, Belgium; KKU: Max Planck Institute for Evolutionary Biology, Ploen, Germany; TZ: Northwest A&F University, Shaanxi, China	

#### Abstract

The analysis of synteny (i.e., conserved gene content and order in a genomic segment across species) can help understand the trajectory of duplicated genes through evolution. In particular, synteny analyses are widely used to investigate the evolution of genes derived from whole-genome duplication (WGD) events, as they can reveal genomic rearrangements that happened following the duplication of all chromosomes. However, synteny analysis are typically performed in a pairwise manner, which can be difficult to explore and interpret when comparing several species. To understand global patterns of synteny, Zhao and Schranz (2017) proposed a network-based approach to analyze synteny. In synteny networks, genes in a given syntenic block are represented as nodes connected by an edge. Synteny networks have been used to explore, among others, global synteny patterns in mammalian and angiosperm genomes (Zhao and Schranz 2019), the evolution of MADS-box transcription factors (Zhao et al. 2017), and infer a microsynteny-based phylogeny for angiosperms (Zhao et al. 2021). syntenet is the first R package that can be used to infer synteny networks from protein sequences and perform downstream network analyses. Synteny detection is performed with a native implementation of the popular MCScanX algorithm, which has been ported to R with the Rcpp framework. Downstream network analyses include: i. network clustering with the Infomap algorithm; ii. phylogenomic profiling, which can reveal highly conserved and taxa-specific synteny clusters; iii. microsynteny-based phylogeny reconstruction with maximum likelihood, which can help elucidate the correct grouping of clades for which alignment-based phylogenies are not clear; iv. network visualization.
