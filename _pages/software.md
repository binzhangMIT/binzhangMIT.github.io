---
title: "Zhang Group - Software"
layout: textlay
excerpt: "Software"
sitemap: false
permalink: software/
---

# Software

(For a full list of source code and simulation results from our publications, go to the group's [GitHub Page](https://github.com/orgs/ZhangGroup-MITChemistry))

## DRAGON
<!--<figure class="fourth">-->
  <!--<img src="{{ site.url }}{{ site.baseurl }}/images/softpic/dragon.png" style="width: 600px">-->
<!--</figure>-->
![]({{ site.url }}{{ site.baseurl }}/images/softpic/dragon.png){: style="width: 300px; float: right; border: 10px"}
DRAGON is a software package to enable De novo, and RAtional prediction of Genome organizatiON. It provides an implementation of the model proposed in the [manuscript](https://journals.plos.org/ploscompbiol/article?rev=2&id=10.1371/journal.pcbi.1007024) to simulate chromatin structure and dynamics. With DRAGON, one can predict cell type specific chromosome structures using genome-wide profiles of histone modifications and CTCF molecules.

The package is mainly written in Python, and it streamlines all the necessary steps to process epigenomics data, to perform molecular dynamics simulations and to analyze predicted conformational ensemble for the chromatin.

## MOFF
MOFF provides implementation of the Maximum entropy Optimized Fore Field introduced in this manuscript ([Latham, A; Zhang, B JCTC, 2019](https://pubs.acs.org/doi/10.1021/acs.jctc.9b00932)) to LAMMPS. The force field is optimized specifically for intrinsically disordered proteins and was shown to predict protein size accurately. 
