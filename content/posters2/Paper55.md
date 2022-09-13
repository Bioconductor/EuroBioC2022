---
title: "Poster: EMMA - Enrichment Methods Matter"
draft: false
type: "blog"
---

## EMMA - Enrichment Methods Matter

Federico Marini,Annekathrin Silvia Ludt

University Medical Center Mainz

#### Abstract

Functional enrichment analysis, performed either via scripted analysis or with web-based tools, is one of the most frequently adopted steps in computational biology, especially when identifying the systems level mechanisms captured by high-dimensional molecular datasets. Recent work (Wijesooriya et al. 2022 - doi: 10.1371/journal.pcbi.1009935) showed that, despite their popularity, methodological issues (e.g. the use of inappropriate background for enrichment, or the lack of detail provided in the Materials and Methods section) might undermine the validity and reproducibility of many research endeavors using (incorrectly) such methods. We acknowledge this by stating that, indeed, Enrichment Methods Matter (EMMA). This proposal aims to define a structured framework to automatically enforce the required rigor when generating or reporting the results for enrichment analyses. It is implemented as an R/Bioconductor package that leverages the current standard containers (such as SummarizedExperiment and its derivatives). Our approach promotes the usage not only of simple tabular formats, as commonly returned by packages and functions to perform enrichment analysis, but also populating in a comprehensive manner the metadata slots of the object designed to store all related information. Ideally, this paradigm of automatically documenting the necessary information should happen in a seamless manner (i.e. without extensive changes to the underlying calls). By doing so, this approach greatly simplifies the (re-)execution of genomic workflows, focusing on computational reproducibility, correct usage of complex yet widely adopted algorithms, and first-class reporting of methods detail when writing scientific reports or manuscripts. We present the work in progress on this, welcoming fruitful discussions on the definition and extension of standards for performing enrichment analyses in simple yet robust and informative frameworks.
