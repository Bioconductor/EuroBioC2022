---
title: "Poster: A corpus of standardized CITE-seq data"
draft: false
type: "blog"
---

## A corpus of standardized CITE-seq data
Bernat Bramon Mora,Helen Lindsay,Raphael Gottardo
Biomedical Data Science Center at the Lausanne University Hospital (CHUV)
#### Abstract

Cell type annotation is one of the central challenges in single-cell analyses, a necessary step for biological interpretation and downstream statistical analyses. While a lot of progress has been made to this date, current state-of-the-art techniques still suffer from major limitations, including lack of ground truth, reliance on limited reference datasets, and lack of standard annotations. Recent advances have introduced methods such as CITE-seq, experimental techniques that measure protein expression of cells in addition to RNA expression. Thanks to these advances, it is now possible to measure the expression of hundreds of proteins in single-cells, potentially facilitating more robust cell-type annotation. Despite their great potential, however, the resulting protein data—also known as antibody derived tags—provide significant analytical challenges, as some of the methods developed for scRNAseq might not be applicable for such data. This is the case of normalisation methods, where the added variability in antibodies makes single-cell RNA normalisation techniques unsuitable for CITE-seq data. Here, we are leveraging public databases to create a corpus of well annotated single-cell data, in an effort to create a large corpus of CITE-seq data that can be used by the computational community to train, test and validate algorithms. In particular, we compile more than 50 published datasets and prepare them as standard Bioconductor objects (e.g. SingleCellExperiment). Then, we perform quality control and standardise cell and feature (gene/protein) metadata. Finally, we propose multiple normalisation methods for antibody derived tags that try to align landmarks in protein density profiles. In this talk, we will discuss our overall pipeline for CITE-seq data standardization, including methodological tools used for the normalisation of protein expression data, and some of the computational infrastructure put in place to process large amount of data.
