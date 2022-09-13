---
title: "Short talk: Smooth epigenomics data analysis and visualisation with Bioconductor (or: an ode to Rle)"
draft: false
type: "blog"
---

## Smooth epigenomics data analysis and visualisation with Bioconductor (or: an ode to Rle)

Pierre-Luc Germain,Mark Robinson	

ETH & University of Zürich	

#### Abstract

Workflows for epigenomics data, especially ATAC/ChIP-like data, typically involve a (sometimes clunky) mix of tools, within and outside R. This can create consistency or reproducibility issues, difficulties when trying to combine elements of different workflows, and complicates teaching. Although excellent R/Bioconductor-based solutions are available for many steps (e.g. Rfastp for QC/trimming, Rsubread for alignment, and several packages for downstream analysis and visualisation), some critical steps lack good R-based alternatives (e.g. peak calling, flexible bigwig file generation). Furthermore, their integration often lacks the smoothness that Bioconductor has allowed us to enjoy in other subfields. In this contribution, I will present an attempt at filling some of these gaps, inviting feedback from (and perhaps involvement of) the community on the endeavour. The effort, currently available through the 'epiwraps' package ( https://github.com/ETHZ-INS/epiwraps ), is very much anchored in core Bioconductor infrastructures, and includes for instance the following features : * Flexible bigwig generation (including efficient Rle-based tiling, neighbourhood-based signal p-values, etc.) * Competitive (MACS-inspired) peak calling * A common, simple and flexible interface for genomic signal visualisation (especially based on Gviz and EnrichedHeatmap), accepting a variety of inputs. * Consistent signal normalisation across tasks (e.g. signal visualisation and differential analysis) The aim is to offer a set of flexible, user-friendly, and interoperable tools for some of the most basic functionalities, and to break the dependency on utilities outside of R. The presentation will showcase some of the main functionalities using ChIP-seq and ATAC-seq examples, present some benchmark results, discuss the rationales behind some of the design choices, and invite discussion as to the way forward (e.g. needs of the community, integration with existing resources).
