---
title: "Poster: SpaceLINCS: an R package to visualise correlations between experimental gene
expression and L1000 perturbagens profiles"
draft: false
type: "blog"
---

## SpaceLINCS: an R package to visualise correlations between experimental gene
expression and L1000 perturbagens profiles
Ivo Kwee, Axel Martinelli, Layal Abo Khayal and Murodhzon Akhmedov. 
BigOmics Analytics, Switzerland
#### Abstract

Accessing the collection of perturbed gene expression profiles, such as the LINCS L1000 connectivity map, is usually performed at the individual dataset level, followed by a summary performed by counting individual hits for each perturbagen. With the SpaceLINCS R package we present an alternative approach that combines rank correlation and gene set enrichment analysis to identify meta-level enrichment at the perturbagen level and, in the case of drugs, at the mechanism of action (MoA) level.  Rather than providing outputs for each perturbation experiment individually, we take the output and perform a meta-level GSEA (Subramanian et al., 2005) by combining them by compound, based on the ranked correlation scores for each experiment. Finally we perform an additional meta-level GSEA computation step to combine compounds into mechanism-of-actions (MoAs) or target genes, to highlight overarching themes in the data. We compared the performance of our method against those of three currently used approaches: EnrichR, SigCom and iLINCS. Overall, the performance of SpaceLINCS is at least comparable (if not slightly superior) to that of iLINCS, the best performing of the three current approaches considered for evaluation.

AVAILABILITY: SpaceLINCS is released under GPL3 license. Source code and documentation are freely available on GitHub (https://github.com/bigomics). An application note will be soon published in Bioinformatics Advances.
