---
title: "Short talk: Tools for CITE-seq preprocessing"
draft: false
type: "blog"
---

## Tools for CITE-seq preprocessing

Helen Lindsay,Bernat Bramon Mora,Raphael Gottardo

Biomedical Data Science Center at the Lausanne University Hospital (CHUV)

#### Abstract

CITE-seq and related technologies use antibody-bound oligo probes to get a quantitative readout of surface protein expression. These technologies have the potential to enable more fine-grained exploration of single cell phenotypes. How best to normalise antibody-derived tag (ADT) expression data and integrate it with other data modalities is an active research area. However, methods development and benchmarking efforts are complicated by the limited availability of readily-comparable CITE-seq data. In particular, there is no gold-standard naming scheme for ADT, which makes it difficult to compare measurements between studies or to integrate gene and surface protein expression measurements from the same study. We have curated a set of publicly available CITE-seq data sets into Bioconductor formats, with standardised names and consistent preprocessing where possible. As part of this effort we have developed tools to assist researchers working with ADT. Here we introduce our package “AbNames”, which provides a manually-curated data set of antibody names and stable IDs for the proteins, protein isoforms, or protein complexes they bind. In addition, AbNames provides functions for reformatting and mapping antibody names — e.g. as provided by an antibody vendor — to gene and protein identifiers, and for renaming ADTs to match a reference data set. We also introduce CITEvis, an R package that allows users to create diagnostic plots for CITE-seq data in SingleCellExperiment or MultiAssayExperiment format.
