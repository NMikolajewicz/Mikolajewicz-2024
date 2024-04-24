# README

## Scripts

All the scripts used to generate figures/results in the current manuscript are listed below. For each script, the appropriate single-cell (Seurat) object must be provided as input as specified in the script itself. All data are publicly available or may be obtained from authors upon reasonable request.

- snRNA-seq clustering, expression, and annotation: `NC1_snRNA-seq_murine_annotation.Rmd`
- In vitro to in vivo transition analyses: `NC2_invitro_to_invivo_transition.Rmd`
- Glioma gene program discovery and comparison: `NC3_glioma_programs.Rmd`
- Immune microenvironment annotation and human comparison: `NC4_immune_microenvironment.Rmd`
- CT2A/GL261 genetic dropout screens and human comparison: `NC5_glioma_essentiality.Rmd`
- Glioma transcriptional regulator discovery analysis: `NC6_GTR_discovery.Rmd`
- Immune coculture screens and evasion phenotypes: `NC7_immune_coculture_screens.Rmd`

## Installation Guide

All analyses were run in R version 4.2.2 using the packages detailed in the “R Session Info” section below. Approximate install/set-up time is 20-30 minutes.

Instructions on how to install R (and RStudio) can be found here: [RStudio Installation Guide](https://rstudio-education.github.io/hopr/starting.html).

Instructions on how to install R packages can be found here: [R Packages Installation](https://rstudio-education.github.io/hopr/packages2.html).

## Instructions for Use

R scripts are provided as Rmarkdown files and are intended to be run in order chunk by chunk to ensure all variables have been appropriately defined for downstream analyses. In sections where data are loaded from local directories, users will have to specify the file location. Following these steps, the key figures that are presented in the manuscript can be reproduced with the provided scripts.

## Demo

The `DEMO_NC7_immune_coculture_screens.Rmd` file has been prepared to demo the utility of the R scripts. Once R and all dependencies have been installed, users may run the script and should expect to reproduce the gene-rank plots presented in Figure 7B. The run time for this script is less than 1 minute.

## System Requirements

R version 4.2.2 (2022-10-31 ucrt)  
Platform: x86_64-w64-mingw32/x64 (64-bit)  
Running under: Windows 10 x64 (build 19045)  

Matrix products: default

locale:  
LC_COLLATE=English_Canada.utf8, LC_CTYPE=English_Canada.utf8, LC_MONETARY=English_Canada.utf8 LC_NUMERIC=C, LC_TIME=English_Canada.utf8

attached base packages:  
parallel, stats, graphics, grDevices utils, datasets, methods,  base

other attached packages:  
glmGamPoi_1.10.0, eshape2_1.4.4, scMiko_0.1.0, doParallel_1.0.17,  iterators_1.0.14, foreach_1.5.2, biomaRt_2.54.0, future_1.29.0, flexdashboard_0.6.0 DT_0.26, gridExtra_2.3, ggplot2_3.4.2, RColorBrewer_1.1-3, tidyr_1.2.1, dplyr_1.0.10, sctransform_0.3.5,  SeuratObject_4.1.3, Seurat_4.2.1

loaded via a namespace (and not attached):  
BiocFileCache_2.6.0, plyr_1.8.7, igraph_1.3.5, lazyeval_0.2.2, sp_1.5-1, splines_4.2.2, listenv_0.8.0, scattermore_0.8, GenomeInfoDb_1.34.2, chk_0.8.1, digest_0.6.30, htmltools_0.5.3, viridis_0.6.2, fansi_1.0.3, magrittr_2.0.3,memoise_2.0.1, tensor_1.5, cluster_2.1.4, ROCR_1.0-11, globals_0.16.1,Biostrings_2.66.0, matrixStats_0.62.0, spatstat.sparse_3.0-0, prettyunits_1.1.1, colorspace_2.0-3,rappdirs_0.3.3, blob_1.2.3, ggrepel_0.9.2, xfun_0.34, RCurl_1.98-1.9, crayon_1.5.2, jsonlite_1.8.3, progressr_0.11.0, spatstat.data_3.0-0, survival_3.4-0, zoo_1.8-11, glue_1.6.2, polyclip_1.10-4, gtable_0.3.1, zlibbioc_1.44.0, XVector_0.38.0, leiden_0.4.3, DelayedArray_0.24.0, future.apply_1.10.0, BiocGenerics_0.44.0, abind_1.4-5, scales_1.2.1, DBI_1.1.3, spatstat.random_3.0-1, miniUI_0.1.1.1, Rcpp_1.0.9, progress_1.2.2, viridisLite_0.4.1, xtable_1.8-4, reticulate_1.26, bit_4.0.4, stats4_4.2.2, htmlwidgets_1.5.4, httr_1.4.4, ellipsis_0.3.2, ica_1.0-3, pkgconfig_2.0.3, XML_3.99-0.12, dbplyr_2.2.1, sass_0.4.2, uwot_0.1.14, deldir_1.0-6, utf8_1.2.2, tidyselect_1.2.0, rlang_1.1.0, later_1.3.0, AnnotationDbi_1.60.0, munsell_0.5.0, tools_4.2.2, cachem_1.0.6, cli_3.4.1, generics_0.1.3, RSQLite_2.2.18, ggridges_0.5.4, evaluate_0.18, stringr_1.4.1, fastmap_1.1.0, ggdendro_0.1.23, yaml_2.3.6, goftest_1.2-3, knitr_1.40, bit64_4.0.5,  fitdistrplus_1.1-8, purrr_0.3.5, RANN_2.6.1, KEGGREST_1.38.0, pbapply_1.5-0, nlme_3.1-160, mime_0.12, xml2_1.3.3, compiler_4.2.2, rstudioapi_0.14, filelock_1.0.2, curl_4.3.3, plotly_4.10.1 png_0.1-7, spatstat.utils_3.0-1, tibble_3.1.8, bslib_0.4.1, stringi_1.7.8, lattice_0.20-45, Matrix_1.5-4.1, tinter_0.1.0, vctrs_0.5.0, pillar_1.8.1, lifecycle_1.0.3, spatstat.geom_3.0-3, lmtest_0.9-40, jquerylib_0.1.4, RcppAnnoy_0.0.20,bitops_1.0-7, data.table_1.14.4, cowplot_1.1.1, irlba_2.3.5.1, GenomicRanges_1.50.1,httpuv_1.6.6, patchwork_1.1.2, R6_2.5.1, promises_1.2.0.1, KernSmooth_2.23-20, IRanges_2.32.0, parallelly_1.32.1, codetools_0.2-18, MASS_7.3-58.1, assertthat_0.2.1,SummarizedExperiment_1.28.0 withr_2.5.0, GenomeInfoDbData_1.2.9, S4Vectors_0.36.0, hms_1.1.2, grid_4.2.2, rmarkdown_2.18, MatrixGenerics_1.10.0, Rtsne_0.16, spatstat.explore_3.0-5, Biobase_2.58.0, shiny_1.7.3
![image](https://github.com/NMikolajewicz/Mikolajewicz-2024/assets/46906473/ec2f80f5-8c02-475c-ad6e-2ee7a429ec2f)
