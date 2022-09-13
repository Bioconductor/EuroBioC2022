---
title: "Poster: MetaboAnnotation: an R package simplifying metabolite annotation"
draft: false
type: "blog"
---

## MetaboAnnotation: an R package simplifying metabolite annotation

Andrea Vicini,Carolin Huber,Michael Witting,Johannes Rainer

Institute for Biomedicine, Eurac Research, 39100 Bolzano, Italy.

#### Abstract

We present the R package MetaboAnnotation designed to assist the end-user in metabolite annotation. Specifically, MetaboAnnotation provides the high level functions matchValues() and matchSpectra() to perform MS1- and MS2-based annotation. The former involves matching of measured m/z values and/or retention times of LC–MS features against reference values; the latter a comparison of potentially generated experimental MS2 spectra against reference spectra, either from in-house or external libraries. The result objects returned by these functions bundle the query and target objects and internally represent the relationships between them in a data frame that also contains the score for each match. Filtering, sub-setting, re-ordering and extracting matches, all potentially error prone operations, are all handled by these result objects. Finally an interactive, shiny-based, validation of matching results is also available with the validateMatchedSpectra() function. The package is a central component of a complete ecosystem facilitating metabolite annotation and is available on Bioconductor.
