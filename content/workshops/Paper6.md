---
title: "Workshop: simplifyEnrichment: A Bioconductor Package for Clustering and Visualizing Functional Enrichment Results"
draft: false
type: "blog"
---

## simplifyEnrichment: A Bioconductor Package for Clustering and Visualizing Functional Enrichment Results

Zuguang Gu

German Cancer Research Center

#### Abstract

Functional enrichment analysis or gene set enrichment analysis is a basic bioinformatics method that evaluates biological importance of a list of genes of interest. However, it may produce a long list of significant terms with highly redundant information that is difficult to summarize. Current tools to simplify enrichment results by clustering them into groups either still produce redundancy between clusters or do not retain consistent term similarities within clusters. We propose a new method named binary cut for clustering similarity matrices of functional terms. Through comprehensive benchmarks on both simulated and real-world datasets, we demonstrated that binary cut can efficiently cluster functional terms into groups where terms showed consistent similarities within groups and were mutually exclusive between groups. We compared binary cut clustering on the similarity matrices obtained from different similarity measures and found that semantic similarity worked well with binary cut, while similarity matrices based on gene overlap showed less consistent patterns. We implemented the binary cut algorithm in the R package simplifyEnrichment, which additionally provides functionalities for visualizing, summarizing, and comparing the clustering. The simplifyEnrichment package and the documentation are available at https://bioconductor.org/packages/simplifyEnrichment/.
