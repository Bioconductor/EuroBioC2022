---
title: "Short talk: Analyzing hydrogen-deuterium exchange mass-spectrometry data in R"
draft: false
type: "blog"
---

## Analyzing hydrogen-deuterium exchange mass-spectrometry data in R

Oliver Crook,Oliver Crook	

University of Oxford	

#### Abstract

A protein’s structure is state-specific and a key determinant of its function. Proteins can undergo subtle structural changes when binding to another protein, small molecule or because of environmental perturbations. Hydrogen deuterium exchange mass spectrometry (HDX-MS) is a technique to explore differential protein structure by examining the rate of deuterium incorporation for specific peptides. This rate will be altered upon structural perturbation and detecting significant changes to this rate requires a statistical test. To determine rates of incorporation, HDX-MS measurements are frequently made over a time course. However, current statistical testing procedures ignore the correlations in the temporal dimension of the data. Using tools from functional data analysis, we develop a testing procedure that explicitly incorporates a model of hydrogen deuterium exchange. To further improve statistical power, we develop an empirical Bayes version of our method, allowing us to borrow information across peptides and stabilize variance estimates for low sample sizes. Our approach has increased power, reduces false positives and improves interpretation over linear model-based approaches. Due to the improved flexibility of our method, we can apply it to a multi-antibody epitope-mapping experiment where current approaches are inapplicable due insufficient flexibility. We will demonstrate a new package “hdxstats” for analyzing HDX-MS data and how to map and visualize the results onto protein structures in R.
