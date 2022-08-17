---
title: "Short talk: spillR: Causal Modelling of Spillover in Mass Cytometry"
draft: false
type: "blog"
---

## spillR: Causal Modelling of Spillover in Mass Cytometry
Marco Guazzini,Alexander Gilbert Reisach,Sebastian Weichwald,Christof Seiler	
Department of Data Science and Knowledge Engineering, Maastricht University	

#### Abstract

In mass cytometry marker interference called `spillover', can cause markers to have higher abundances than their true abundances. Chevrier and Crowell et al.~2018 introduced an experimental and computational procedure to estimate spillover and compensate for it in downstream analyses. Their R package CATALYST implements this in two steps: estimate spillover and remove spillover from data. We propose a method that combines estimation and correction in one step, in order to quantify uncertainty and improve data efficiency. Building on a hierarchical causal model that represents the spillover from one marker to another, we extend the usual negative binomial model by modifying the link function using information from the spillover matrix. Our simulations show that an explicit causal model has two advantages: We control false positive errors even in noisy settings and improve statistical power when the causal model is correctly specified. We will present our new R package spillR and vignettes for reproducibility.
