---
title: "Poster: LMWiRe: an R package for Linear Modeling of Wide Responses based on ASCA family of methods"
draft: false
type: "blog"
---

## LMWiRe: an R package for Linear Modeling of Wide Responses based on ASCA family of methods

Michel Thiel,Nadia Benaiche,Manon Martin,Sébastien Franceschini,Robin Van Oirbeek,Bernadette Govaerts

UCLouvain

#### Abstract

Many modern analytical methods are used to analyze samples issued from an experimental design; for example in medical, biological, chemical or agronomic fields. Those methods generate most of the time highly multivariate data like spectra or images, where the number of variables (descriptors) tends to be much larger than the number of experimental units. Therefore, multivariate statistical tools are needed to highlight variables that are consistently modified by experimental factors. In this context, two recent methods combining ANOVA and PCA, namely ASCA (ANOVA-Simultaneous Component Analysis) and APCA (ANOVA-Principal Component Analysis), were developed. They provide powerful visualization tool for multivariate structures in the space of each effect of the statistical model linked to the experimental design. Their main limitation is that they produce biased estimators of the factor effects when the design of experiment is unbalanced. This article presents the R package LMWiRe (Linear Models for Wide Responses) which implements ASCA+ and APCA+, an enhanced version of ASCA and APCA methods based on several principles from the theory of General Linear Models (GLM). In this paper the methodology is reviewed, the package structure and functions are presented, and a real-life metabolomics data set is used to clearly demonstrate the potential of ASCA+ and APCA+ methods to highlight true biomarkers corresponding to effects of interest in unbalanced designs.
