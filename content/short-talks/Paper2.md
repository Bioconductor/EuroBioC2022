---
title: "Short talk: DifferentialRegulation: a novel approach to identify differentially regulated genes."
draft: false
type: "blog"
---

## DifferentialRegulation: a novel approach to identify differentially regulated genes.
Simone Tiberi,Joël Meili,Mark Robinson	
University of Zurich	

#### Abstract

Background. Technological developments have led to an explosion of high-throughput single cell data, which are revealing unprecedented perspectives on cell identity. Recently, significant attention has focused on investigating cellular dynamic processes, such as cell differentiation, cell (de)activation, and gene regulation. In particular, RNA velocity tools (notably velocyto and scVelo), by exploiting the abundance of spliced (mature) mRNA and unspliced (immature) pre-mRNA, enable inferring the RNA velocity of individual cells, i.e., the time derivative of the gene expression state of cells. Aim and impact. Here, we introduce DifferentialRegulation, a novel instrument to further investigate gene regulation from scRNA-seq data. In particular, we present a rigorous statistical framework to perform differential regulation analyses between experimental conditions, by discovering differences in the balance (i.e., relative abundance) of spliced and unspliced mRNA. Intuitively, a higher proportion of unspliced (spliced) mRNA in a condition suggests that a gene is currently being up- (down-) regulated compared to the other condition. Our tool will allow researchers to deeper study how gene regulation varies between groups of samples (e.g., healthy vs. disease or treated vs. untreated) identifying differentially regulated genes in specific populations of cells (e.g., cell-types specific changes in regulation). For instance, it was shown that c-Myc regulated genes are subject to up-regulation in cancer cells: our method will be ideal to investigate such scenarios and identify what genes and differentially regulated in cancer in what cell-type. Importantly, the method we consider is flexible and can input any type of scRNA-seq data. Methodology. The abundance of spliced and unspliced mRNA reads can be inferred with pseudo-aligner tools such as alevin, alevin-fry and kallisto-bustools. However, in popular droplet scRNA-seq protocols, many reads (~5-40% [1-2]) have uncertain gene allocation and map to multiple genes. Furthermore, an even larger fraction of reads (~30-40% in our real data analyses [3-4]) is “ambiguous” and compatible with both spliced and unspliced versions of a gene. Therefore, estimated spliced and unspliced counts carry a significant degree of uncertainty, which should be accounted for by downstream methods. Here, we propose a Bayesian model that inputs equivalence classes of reads, i.e., the list of genes and spliced/unspliced version of genes each read is compatible with. Our method treats both gene and spliced/unspliced allocations of reads as latent states and samples them within a Markov chain Monte Carlo scheme. Furthermore, to account for the variability between biological replicates, we embed multiple samples in a hierarchical model, which enables sharing of information across replicates while allowing for sample-specific parameters. The posterior distributions of the parameters is inferred via MCMC techniques where model parameters and latent states are alternately sampled. Therefore, our method explicitly models two major sources of variability: i) the sample-to-sample variability between biological replicates, and ii) the mapping uncertainty. From a computational perspective, despite relying on MCMC algorithms, our method is coded in C++ (via the Rcpp interface), and displays efficient computational performance by completing a full differential analysis within a few minutes on a laptop. Benchmarking. We performed extensive benchmarks of our method and two competitors, eisaR and BRIE2, both of which use estimated spliced and unspliced reads and neglect mapping uncertainty. In particular, we simulated two multi-sample multi-group scRNA-seq datasets, at the read level with minnow, and show that our tool displays significantly higher statistical power than competitors while controlling for the false discovery rate. When analyzing real biological data[3-4], we further show that false positive rates are well calibrated in a null data (i.e., where no differential effects are expected), and that our discoveries are more coherent with the current biological knowledge than competitors’. Availability. DifferentialRegulation is available on Bioconductor. References. [1] Dharshini, et al. Identifying suitable tools for variant detection and differential gene expression using RNA-seq data. Genomics (2020). [2] McDermaid et al. A new machine learning-based framework for mapping uncertainty analysis in RNA-Seq read alignment and gene expression estimation. Frontiers in genetics (2018). [3] Park et al. Single-cell transcriptomics of the mouse kidney reveals potential cellular targets of kidney disease. Science (2018). [4] Velasco et al. Individual brain organoids reproducibly form cell diversity of the human cerebral cortex. Nature (2019).