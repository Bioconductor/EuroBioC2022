---
title: "Poster: Differential transcript usage analysis for dynamic biological processes"
draft: false
type: "blog"
---

## Differential transcript usage analysis for dynamic biological processes

Jeroen Gilis,Koen Van den Berge,Lieven Clement

Ghent University

#### Abstract

Trajectory inference has been instrumental for modelling dynamic changes in biological systems during processes like cell differentiation, tissue development and response to external stimuli. Downstream of trajectory inference, one key challenge is the identification of marker genes that are associated with the dynamic process at hand. In this context, our Bioconductor package tradeSeq is a highly flexible and scalable tool that allows for testing both within-lineage and between-lineage changes in gene expression.  One drawback of tradeSeq is that it only allows for performing differential expression analyses, either at the level of genes (differential gene expression, DGE) or transcripts (differential transcript expression, DTE). However, it has been shown extensively that most multi-exon genes are subject to alternative splicing and can thus produce a variety of functionally different transcripts from a single genomic locus. In this context, the biological question of interest also lies in assessing the change in relative usage of transcripts within the same gene (differential transcript usage, DTU). Several Bioconductor packages like DEXSeq, DRIMSeq and our package satuRn implement differential transcript usage tests, but are limited to comparisons between discrete groups of sample or cells.  We here extend tradeSeq for testing DTU along trajectories. We model transcript usage as a smooth function of (pseudo-)time by means of a quasibinomial generalized additive model. Like the gene-level test in tradeSeq, DTU can be subsequently tested both within a lineage and between lineages. Our extension essentially unlocks tradeSeq for DTU inference and satuRn for comparisons along continuous processes. In a case study, we use our extended tradeSeq suite to test for DGE, DTE and DTU during the process of endoderm differentiation. On the one hand, this allows us to pinpoint which exact transcript-level changes in expression are underlying the differential expression signal at the gene level (DTE versus DGE). On the other hand, it allows us to identify genes that have constant overall expression levels during the differentiation process, but for which the underlying attribution of reads to the different transcripts is changing (DGE versus DTU).
