---
title: "Poster: decoupleR: ensemble of computational methods to infer biological activities from omics data"
draft: false
type: "blog"
---

## decoupleR: ensemble of computational methods to infer biological activities from omics data

Pau Badia i Mompel

Heidelberg University, Faculty of Medicine, and Heidelberg University Hospital, Institute for Computational Biomedicine, BioQuant, Heidelberg 69120, Germany

#### Abstract

Many methods allow us to extract biological activities from omics data using information from prior knowledge resources, reducing the dimensionality for increased statistical power and better interpretability. Here, we present decoupleR, a Bioconductor and Python package containing computational methods to extract these activities within a unified framework. decoupleR allows us to flexibly run any method with a given resource, including methods that leverage mode of regulation and weights of interactions, which are not present in other frameworks. Moreover, it leverages OmniPath, a meta-resource comprising over 100 databases of prior knowledge. Using decoupleR, we evaluated the performance of methods on transcriptomic and phospho-proteomic perturbation experiments. Our findings suggest that simple linear models and the consensus score across top methods perform better than other methods at predicting perturbed regulators. decoupleR’s open-source code is available in Bioconductor (https://www.bioconductor.org/packages/release/bioc/html/decoupleR.html) for R and in GitHub (https://github.com/saezlab/decoupler-py) for Python. The code to reproduce the results is in GitHub (https://github.com/saezlab/decoupleR_manuscript) and the data in Zenodo (https://zenodo.org/record/5645208).
