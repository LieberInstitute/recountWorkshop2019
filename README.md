# Using the recount2 resource and related tools
[![DOI](https://zenodo.org/badge/175835474.svg)](https://zenodo.org/badge/latestdoi/175835474)

# Instructor

Leonardo Collado-Torres

* [GitHub](https://github.com/lcolladotor)
* [Twitter](https://twitter.com/fellgernon)
* [Email](mailto:lcolladotor@gmail.com)

# Workshop Description

The recount2 project re-processed RNA sequencing (RNA-seq) data on over 70,000 human RNA-seq samples spanning a variety of tissues, cell types and disease conditions. Researchers can easily access these data via the `recount` Bioconductor package, and can quickly import gene, exon, exon-exon junction and base-pair coverage data for uniformly processed data from the SRA, GTEx and TCGA projects in R for analysis. This workshop will include an overview of the recount2 project as well as methods and tools that have been to improve it since 2017. The overview will be followed by a hands-on session where you will dive into `recount` and related packages along the lines of the [recount workflow](http://bioconductor.org/packages/release/workflows/html/recountWorkflow.html).

In more detail, this workshop will cover different use cases of the `recount` package, including downloading and normalizing data, processing and cleaning relevant phenotype data (including `recount-brain`), performing differential expression (DE) analyses, and creating reports for exploring the results using other Bioconductor packages. The workshop will also cover how to use the base-pair coverage data for annotation-agnostic DE analyses and for visualizing coverage data for features of interest. After taking this workshop, attendees will be ready to enhance their analyses by leveraging RNA-seq data from 70,000 human samples.

[recount2 website](https://jhubiostatistics.shinyapps.io/recount/), [recount package](http://bioconductor.org/packages/recount), [paper](http://www.nature.com/nbt/journal/v35/n4/full/nbt.3838.html), [recount workflow](http://bioconductor.org/packages/release/workflows/html/recountWorkflow.html).

## Pre-requisites

* Basic knowledge of R syntax
* Basic knowledge of RNA-seq or gene expression data
* Familiarity with the RangedSummarizedExperiment class
* Familiarity with SummarizedExperiment [vignette](http://bioconductor.org/packages/release/bioc/vignettes/SummarizedExperiment/inst/doc/SummarizedExperiment.html)

If you are curious, we taught a similar workshop at [BioC2017](http://research.libd.org/recountWorkshop/) that will be updated for this BioC2019. That original workshop lead to the [recount workflow](http://bioconductor.org/packages/release/workflows/html/recountWorkflow.html) which we also plan to update this year.

## Workshop Participation

Students are expected to ask questions during the recount2 overview presentation and to bring their own laptop so they can follow the hands-on portion of the workshop.

## _Bioconductor_ packages used

`SummarizedExperiment`, `recount`, `GenomicRanges`, `DESeq2`, `derfinder`, `regionReport` are among the packages that will be explicitly covered.

## Time outline

| Activity                     | Time |
|------------------------------|------|
| recount2 project and updates overview                    | 30m  |
| break 1 / package setup and troubleshooting | 5 min |
| accessing gene count data with recount          | 15m  |
| using recount-brain | 15m   |
| break 2 | 5 min |
| in depth example analysis | 30m  |
| closing remarks | 5m |

Total: 1h 45 min.

# Workshop goals and objectives

## Learning goals

* Understand the publicly data available via the recount2 project beyond gene counts
* Identify how recount2 data could be useful for your RNA-seq projects and how you can use it
* Describe the annotation-agnostic methods powered by recount2 that complement other RNA-seq analysis pipelines

## Learning objectives

* Re-analyze public RNA-seq data using the recount Bioconductor package
* Recognize how to access the different types of data hosted by recount2
* Locate resources that enhance recount2 such as recount-brain and review how to use them
* Produce a HTML report of a differential expression analysis
