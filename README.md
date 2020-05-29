# Importing alevin scRNA-seq counts into R/Bioconductor

# Instructor(s) name(s) and contact information

- Michael Love (michaelisaiahlove at gmail dot com)
- Avi Srivastava (asrivastava at nygenome dot org)

# Workshop Package:

<https://github.com/mikelove/alevin2bioc>

# Workshop Description

In this workshop, we will demonstrate basics of quantification of
droplet-based scRNA-seq reads using alevin, producing a count matrix 
for import into Bioconductor using tximeta, in the end 
producing a *SingleCellExperiment* object. We will also demonstrate
the ability of alevin to provide quantification uncertainty on the 
count matrix, and visualize this uncertainty across cells.

We plan the workshop to be an instructor-led live demo with time
for questions and interactions with the participants. We imagine that
the target participant for the workshop probably has some dscRNA-seq 
data, and knows about e.g. generating a count matrix with *CellRanger*.
We will show an alternative quantification pipeline and explain its
benefits. We will show hand off of the data to OSCA (Bioconductor's
online book) as well as to Seurat.

## Pre-requisites

* Basic knowledge of R syntax
* General understanding of scRNA-seq experiment

## Workshop Participation

Students will participate by following along a live demo, and asking
questions or providing feedback throughout.

## _R_ / _Bioconductor_ packages used

- tximeta
- SingleCellExperiment
- fishpond
- scran
- Seurat

## Time outline

An example for a 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| alevin for droplet scRNA-seq | 20m  |
| importing counts into Bioc   |  5m  |
| examination of counts data   | 10m  |
| examination of uncertainty   | 10m  |

# Workshop goals and objectives

## Learning goals

- understand how scRNA-seq quantification methods work and 
  understanding their limits
- describe how Bioconductor's classes including
  *SingleCellExperiment* facilitate reproducibility through 
  tracking metadata on the samples/cells and the genomic ranges

## Learning objectives

- see code to run alevin, quantifying scRNA-seq reads to make a gene count matrix
- import scRNA-seq count data including genomic ranges
- manipulate a SingleCellExperiment
- examine scRNA-seq counts over cell labels
- examine uncertainty estimates for counts
- hand-off to Seurat workflow
- hand-off to OSCA workflows
