---
title: "Short talk: DeeDee - Evaluating, Visualizing, and Integrating Results from Differential Expression Analysis Workflows"
draft: false
type: "blog"
---

## DeeDee - Evaluating, Visualizing, and Integrating Results from Differential Expression Analysis Workflows
Federico Marini,Lea Rothörl	
University Medical Center Mainz	

#### Abstract

Differential expression (DE) analysis is employed ubiquitously as a bioinformatic workflow to study the patterns of gene regulation, and established methods and software tools support the execution of this step, from the command line as well as via interactive web application, simplifying their adoption in the context of individual endeavors. The ease of generating larger, complex datasets encompassing a multitude of experimental conditions, together with the increasing need of contextualizing the own DE results within the wealth of information available at public repositories, has led researchers to perform comparisons and integrative analyses, where they efficiently combine the information from multiple DE results. The Bioconductor ecosystem offered an ideal framework to develop a tool for this purpose, finding differential expression patterns of interest across different contrasts, helping the researcher make sense of their data at a more holistic level (e.g. joint regulatory mechanisms, or those unique to specific setups). We propose the DeeDee package, with a set of functionality to summarize, visualize, and interpret any combination of DE results from the main modeling algorithms (DESeq2, edgeR, limma) where a common set of features is included. DeeDee extracts the relevant information from each provided contrast, and offers graphical and set-based representations, intended to better define the (dis)agreement over transcriptome profiles. The standalone functions are also leveraged in a Shiny web application that covers commonly executed drill-down operations, making DeeDee accessible and usable by a wide range of professionals, streamlining these operations up to the creation of publication-ready output. We expect this tool to become useful in the context of many research efforts, simplifying the knowledge extraction from complex transcriptomic datasets, and possibly making this approach amenable in scenarios where multiple omics layers are being assayed. DeeDee is freely available under https://github.com/lea-rothoerl/DeeDee.
