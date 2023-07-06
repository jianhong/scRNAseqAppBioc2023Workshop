Package demo for scRNAseqApp
================
Authors: Jianhong Ou[^1]<br/>
Last modified: 2023-07-06

## Overview

### Description

Single-cell RNA sequencing (scRNA-seq) is a powerful technique to study
gene expression, cellular heterogeneity, and cell states within samples
in single-cell level. The development of scRNA-seq shed light to address
the knowledge gap about the cell types, cell interactions, and key genes
involved in biological process and their dynamics. To precisely meet the
publishing requirement, reduce the time of communication the
bioinformatician with researchers, and increase the re-usability and
reproducibility of scientific findings, multiple interactive
visualization tools were developed to provide the researchers access to
the details of the data. Based on ShinyCell, the scRNAseqApp package is
developed with multiple highly interactive visualizations of how cells
and subsets of cells cluster behavior for scRNA-seq, scATAC-seq and
sc-multiomics data. The end users can discover the expression of genes
in multiple interactive manners with highly customized filter conditions
by selecting metadata supplied with the publications and download the
ready-to-use results for republishing.

### Pre-requisites

- Basic knowledge of R syntax
- Basic knowledge of Docker
- Basic knowledge of shell commands
- Basic knowledge of Shiny
- A computer with internet connection

### Participation

Attendance must be familiarity with scRNAseq analysis and know the data
structure of [Seurat](https://satijalab.org/seurat/) object.

### *R* / *Bioconductor* packages used

- [*scRNAseqApp*](https://bioconductor.org/packages/scRNAseqApp/)

### Time outline

An example for a 45-minute workshop:

| Activity                      | Time |
|-------------------------------|------|
| Introduction of *scRNAseqApp* | 10m  |
| Sample code explanation       | 15m  |
| Hands-on workshop             | 10m  |
| Q & A                         | 10m  |

### Workshop goals and objectives

### Learning goals

- Gain the knowledge of typical workflows for creating a shiny APP via
  *scRNAseqApp* package
- Understand the user management system of the APP.
- Learn the available visualization tools provided by the package

### Learning objectives

- Learn how to set up a shiny APP via *scRNAseqApp* package
- Learn how to add a new data to the APP
- Learn how to distribute the APP to a shiny server

[^1]: Regeneration Center, Duke University, Durham, North Carolina, USA.
