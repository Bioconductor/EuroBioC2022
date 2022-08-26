---
title: "Poster: Viewing Several Interactive Plots with Plotly and Trelliscopejs: A Lipidomics Data Example"
draft: false
type: "blog"
---

## Viewing Several Interactive Plots with Plotly and Trelliscopejs: A Lipidomics Data Example
Jeremy John Selva
National University of Singapore
#### Abstract

In a typical lipidomics workflow, many quality checks are done to evaluate samples measured for a particular transition. This results in several quality control plots for each transition which are converted as pages in a pdf file. However, as technologies improved, many transitions can be measured in one sample at a fast rate. Today, just from targeted lipidomics workflow using liquid chromatography, over 500 transitions can be easily be measured on large studies of up to a few thousand samples.   Having a data analyst to look at a 500 page pdf file showing a static plots of a few thousand sample has its limitations. Thus, a more interactive approach is required.    This workshop introduces a simple lipidomics related transitions quality checking workflow which involves   Plotting using R package plotly from scratch (ggplot2 is not used) 1. Injection Sequence vs Peak Area scatter plot  2. Raincloud plots (or violin plot) of different QC types 3. How to put them two plotly plots together like patchwork using R package manipulateWidget 4. How to output plotly plots using R package htmlwidgets  Create Lipidomics Transition metadata using Bioconductor package rgoslin  Using R package Trelliscopejs to 1. View many plotly plots efficiently 2. Learn how to create cognostics from the transition metadata and related QC statistics so that we can filter the plots easily in Trelliscopejs 3. Learn how to output Trelliscopejs output in a (non-self contained) html file to be compressed in a folder and distribute to other people. While it is possible to output this in a self-contain file, the html file may be too big and cannot be read.

#### Date: Wednesday