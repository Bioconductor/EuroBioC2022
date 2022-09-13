---
title: "Short talk: Simplified, strand aware and comprehensive splicing analysis using IntEREst (1.22.0)."
draft: false
type: "blog"
---

## Simplified, strand aware and comprehensive splicing analysis using IntEREst (1.22.0).

Ali Oghabian,Mikko Frilander	

Folkhälsan Research Center & University of Helsinki	

#### Abstract

Previously several tools were developed that can be used to perform alternative splicing analysis, e.g. DEXSeq, Cufflinks, and Whippet. Intron retention (IR) is, however, not easily detected due to peculiar characteristics of the introns and IR transcripts: introns are normally much lengthier compared to exons; therefore, they require more sequence reads to cover their length; introns feature more repetitive sequence elements i.e. regions which usually a smaller number of sequence reads map accurately; some introns feature non-coding RNAs (e.g. miRNAs and snoRNAs) which, if expressed, may influence the read-counts of those introns; Isoforms with retained introns can be low in abundance. Intron Exon Retention Estimator (IntEREst) is an R/Bioconductor software package that provides comprehensive read summarization tools that are useful for studying RNA splicing, and in particular intron retention. Currently, it supports tools that quantify reads that span the introns, skip the exons, map to the introns and map to the intron-exon junction. Furthermore, it provides tools that calculate the Percentage Spliced In (PSI) for intron retention and carryout statistical differential retention analysis of the introns. We aim to add several useful features to IntEREst in the upcoming releases: 1. Exon inclusion level estimation: The capability to estimate the inclusion level (PSI) of the exons for a number of selected of transcripts. 2. strand-awareness: IntEREst will also take the strands of the reads into account for stranded RNAseq data. this facilitates accurate estimation of the intron retention in the overlapping genes that are on the opposite strands. 3. Implementation of wrapper functions: We have already described in a vignette document the full sequence of functions that one can use to construct the required references, summarize read counts and eventually run differential intron retention analysis. we will implement a wrapper function that simplifies running of the correct sequence of functions based on the type of analysis that the user requests (e.g. Intron retention PSI estimation, differential intron retention, exon inclusion PSI estimation and etc). 4. Performance improvement: We also aim to improve the memory usage and the run time of the analysis. It is worth mentioning that few of the updates have already been implemented in the development version of IntEREst (1.21.1). As for instance it is possible to quantify the number of sequence reads that skip the exons. This is useful for measuring the exon inclusion levels of the exons. Further updates are also planned to implemented in the near future.
