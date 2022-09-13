---
title: "Short talk: Differential embedding analysis of multi-condition single-cell datasets"
draft: false
type: "blog"
---

## Differential embedding analysis of multi-condition single-cell datasets

Constantin Ahlmann-Eltze,Wolfgang Huber	

EMBL Heidelberg	

#### Abstract

Multi-condition single-cell datasets enable the investigation of cell population-specific treatment effects. For the analysis, cell populations are typically matched across conditions by clustering and applying non-linear transformations. However, discretizing continuous latent structures and the non-linear matching sacrifice statistical power, complicate interpretation, and are difficult to validate. Here, we suggest a new framework, called differential embedding analysis, to perform regression analysis on the low dimensional embeddings of the cells in the gene-space for each condition. We implement a rotation manifold-based geodesic regression method that disentangles the variance of the data due to the inherent cell population variability and the variation due to the treatment. Our method is based on a continuous latent variable model and finds a linear transformation to embed cells from all conditions in a single latent space. We demonstrate that our model can identify cell populations affected by the treatment, independent of predefined cluster boundaries, and how gene expression changes differ across cell populations.
