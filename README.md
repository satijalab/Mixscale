# Mixscale 
Mixscale is an R package designed to analyze CRISPR interference (CRISPRi) based Perturb-seq data. It can quantify the heterogeneity of perturbation strength in each cell and improve the statistical power when doing differential expression (DE) analysis. It also provides functions for downstream analyses including decomposition, permutation test, gene set enrichment test, etc. A brief vignette is available at https://satijalab.github.io/Mixscale/.

## Dependencies
This package depends on several other R packages:
```
install.packages("Seurat")
install.packages("PMA")
install.packages("protoclust")
BiocManager::install("glmGamPoi")
```

## Installation 
You can easily install the package by the following command:
```
devtools::install_github("satijalab/Mixscale")
```

## Other resources
* Our preprint is available at https://www.biorxiv.org/content/10.1101/2024.01.29.576933v2.
* If you want to access the data generated in our paper (including the processed scRNA-seq data and the pathway gene signatures), you can download them at https://doi.org/10.5281/zenodo.14518762. 
* Raw fastq files are available at the Gene Expression Omnibus (GEO) under the accession code [GSE281048](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE281048).

