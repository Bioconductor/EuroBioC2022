---
title: "Short talk: DepInfeR - A Bioconductor package for Inferring tumor-specific cancer dependencies through integrating ex-vivo drug response assays and drug-protein profiling"
draft: false
type: "blog"
---

## DepInfeR - A Bioconductor package for Inferring tumor-specific cancer dependencies through integrating ex-vivo drug response assays and drug-protein profiling
Alina Batzilla,Junyan Lu,Wolfgang Huber	
Medical Faculty Heidelberg, University of Heidelberg	

#### Abstract

The development of cancer therapies may be improved by the discovery of tumor-specific molecular dependencies. The requisite tools include genetic and chemical perturbations, each with its strengths and limitations. Drug perturbations can be readily applied to primary cancer samples at a large scale, but mechanistic understanding of hits and further pharmaceutical development is often complicated by the fact that a small compound has a range of affinities to multiple proteins. To computationally infer the molecular dependencies of individual cancers from their ex-vivo drug sensitivity profiles, we developed DepInfeR, a mathematical model and a Bioconductor package that deconvolutes these data using measurements of protein-drug affinity profiles. DepInfeR correctly identified known dependencies, including EGFR dependence in Her2+ breast cancer cell line, FLT3 dependence in AML tumors with FLT3-ITD mutations and the differential dependencies on the B-cell receptor pathway in two major subtypes of chronic lymphocytic leukemia (CLL). Furthermore, our method uncovered new subgroup-specific dependencies, including a previously unreported dependence of high-risk CLL on Checkpoint kinase 1 (CHEK1). The method also produced a more accurate map of the molecular dependencies in a heterogeneous set of 117 CLL samples. The ability to deconvolute polypharmacological phenotypes into underlying causal molecular dependencies should increase the utility of high-throughput drug response assays for functional precision oncology.
