<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->
<!-- badges: end -->

# CISR tutorial: Introduction to single cell RNA-seq analysis

<p align="center">
<img width="350" alt="uwccc2021" src="https://github.com/welch16/cisr2021singlecellRNA/blob/main/man/figures/Carbone_color-center.png?raw=true"/>
</p>

This material as created for the *Practical Bioinformatics Tools for
Cancer Omics* session in the [UWCCC research retreat
2021](https://cancer.wisc.edu/research/retreat/).

## Instructor names and contact information:

-   Irene Ong <irene.ong@wisc.edu>
-   Sean Mcilwain <sean.mcilwain@wisc.edu>
-   Peng Liu <pliu55@wisc.edu>
-   Philippos Tsourkas <tsourkas@biostat.wisc.edu>
-   Rene Welch <rwelch2@wisc.edu>

## Pre-requisites

-   Basic knowledge of R and Rstudio

## Required tools

We require to use:

-   [R statistical software](https://www.r-project.org/),
-   [Rstudio](https://rstudio.com/products/rstudio/download/#download)
    (not strictly necessary but the easiest alternative to work with R)

## R packages

After installing RStudio, these are the packages we may use:

    install.packages("tidyverse")
    install.packages("Seurat")
    install.packages("BiocManager")
    install.packages("plotly")
    BiocManager::install("scRNAseq") ## to get a dataset
