---
title: "Poster: miaSim: a time series simulation R package for microbial ecology"
draft: false
type: "blog"
---

## miaSim: a time series simulation R package for microbial ecology

Yagmur Simsek,Yu Gao,Daniel Rios Garza,Karoline Faust,Leo M Lahti	

Department of Computing, University of Turku, Finland	

#### Abstract

Hundreds to thousands of species interact in natural microbial communities. Computer simulations in microbiome ecology are therefore becoming increasingly important to understand the interactions between species. In this script, we introduce miaSim: a time series tool to simulate microbiome ecology, a new open-source, publicly available R package modelling microbial population dynamics in a repeatable, transparent, and scalable manner. miaSim consists of three major components: simulation functions, tools for preparing initial states and environmental conditions for a set of samples and not but not least random time series sampling. Starting from a core implementation of four widely used ecological models (namely the stochastic logistic, MacArthur’s consumer-resource, Hubbell’s neutral, and generalized Lotka-Volterra models) and several of their derivations, miaSim provides users with a broad range of possibilities to match their specific assumptions and scenarios. Furthermore, the models share the same data structure and, whenever possible, share control parameters, such as temporal dynamics, generation of initial states, metacommunity structure, and controls over stochasticity and external perturbations. This significantly facilitates cross-model combination, comparison, and integration with metagenomic sequencing datasets. Moreover, by revisiting published experiments and by replicating and/or expanding some of their assumptions, we validated miaSim’s reliability, robustness, and user-friendliness. Data containers that can store the hierarchical structure along with the biological profile are important to manipulate and easily access microbiome data. Therefore, miaSim utilizes the data containers SummarizedExperiment and TreeSummarizedExperiment. All results of the simulations can be stored in one of these data containers, depending on their characteristics. miaSim is accompanied by miaSimShiny, an accessible and interactive interface that allows users to explore the parameter space of their models in real-time. We anticipate that miaSim will significantly facilitate the task of simulating microbiome dynamics, highlighting the role of ecological simulations as important tools in the microbiome research toolbox. While complexes in silico microbiomes fall short of being a complete portrayal of microbiome communities due to the limitations, they do capture broad characteristics that are expected to be major driving forces in natural microbiomes.

#### Date: Thursday
