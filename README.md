mitology Workflow: scRNAseq and ST
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

This repository contains the scripts for data processing, enrichment
computation and figure generation on single-cell (SC) and spatial
transcriptomics (ST) data with mitology.

<img src=./mitology_main_figure.png />

A single .Rmd file is provided for each dataset analysis.

## Required Packages

The `mitology` package can be installed from Bioconductor:

``` r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("mitology")
```

Further, to run the workflows, the `batchelor`, `GEOquery`, `graphite`,
`GSVA`, `Matrix`, `rhdf5`, `scater`, `scran`, `scuttle`,
`SingleCellExperiment`, `SpatialExperiment` R packages are required.

## Documentation and Contacts

Further details on how to use `mitology` are available in the
[vignette](https://bioconductor.org/packages/release/bioc/vignettes/mitology/inst/doc/mitology.html),
that includes examples and documentation.

For any problems in using `mitology`, please write to
<stefania.pirrotta@unipd.it>.
