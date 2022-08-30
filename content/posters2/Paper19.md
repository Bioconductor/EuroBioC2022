---
title: "Poster: ProFaNA - Neighborhood analysis for prediction of gene function"
draft: false
type: "blog"
---

## ProFaNA - Neighborhood analysis for prediction of gene function
Bartosz Baranowski,Krzysztof Pawłowski
Institute of Biochemistry and Biophysics, Polish Academy of Sciences
#### Abstract

Many genes in microbial genomes remain functionally uncharacterized. Understanding signaling and metabolic pathways involving such genes is essential for deeper understanding of microbial biology and also mechanisms of infectious diseases. It is well known that groups of genes neighboring in the genome are more likely to share similar biological functions than random pairs of genes. For example in prokaryotic genomes functionally coupled genes can be organized in conserved gene clusters enabling their coordinated regulation. This has been exploited in some bioinformatic tools for functional relationship prediction, e.g., STRING, COGNAT or G-NEST.  Standard gene neighborhood analysis approaches suffer from uneven sampling of the microbial world by genome sequencing projects, e.g., there are hundreds of available genomes of different Escherichia coli strains. Hence, we propose a novel approach to investigate functional enrichment of genomic neighborhoods. We consider over 80 000 prokaryotic genomes. For homologues of the query gene, we analyze all genomic neighborhoods and perform a statistical analysis of occurrence of protein functional domains (Pfam domains) within neighborhoods. To minimize bias resulting from uneven genome space sampling, our algorithm allows collapsing the neighborhood analysis at different taxonomic levels (e.g., species or genera) and limiting the analysis to selected taxonomic groups. A rigorous statistical assessment with provision for multiple testing is provided. Thus, sets of significantly co-occurring functional domains can be elucidated for query genes. The method is implemented in a publicly available server. Usage example is provided for the SelO/YdiU family, an ubiquitous and evolutionarily conserved group recently shown by our group to be AMPylators involved in oxidative stress response.
