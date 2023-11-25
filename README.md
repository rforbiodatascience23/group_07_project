# group_07_project

## Project contributors:

-   Sarah Rosenberg Asmussen (s194689)

-   Mette Bøge Pedersen (s194679)

-   Caroline Amalie Bastholm Jensen (s213427)

-   Jaime Noguera Piera (s233773)

-   Yassine Turki (s231735)

## Project Description

In this project, we investigate a gene expression dataset for patients with bladder cancer. Our data was acquired from the National Center for Biotechnology Information <https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE31684>. It consists of microarray data from 93 bladder cancer patients. Our goal in this project is to investigate the correlation between gene expression and metastasis occurrence. We are also interested in assessing the relevance of smoking when looking at metastasis, and we looked at the regulation of the genes of this population when it comes to metastasis.

## Data retrieval

We have implemented a programmatic retrieval for the data in the 01_load.qmd file. We download 2 datasets: one solely containing the gene expressions for our patients and another dataset containing information about the patients, such as age, smoking, metastasis, etc.

We join these two datasets to create the 01_dat_load.tsv dataset, which contains both the metadata and the gene expression.

## Analysis

Run the 00_all.qmd file to render the full analysis.
