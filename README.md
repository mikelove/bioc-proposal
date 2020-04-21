# Quantification of droplet scRNA-seq and import into Bioconductor with alevin and tximeta

# Instructor(s) name(s) and contact information

- Michael Love (michaelisaiahlove at gmail dot com)
- Avi Srivastava (asrivastava at nygenome dot org)

# Workshop Description

In this workshop, we will demonstrate basics of quantification of
droplet-based scRNA-seq reads using alevin, producing a count matrix 
for import into Bioconductor using tximport/tximeta, in the end 
producing a *SingleCellExperiment* object. We will also demonstrate
the ability of alevin to provide quantification uncertainty on the 
count matrix, and suggestions for how this information can be used 
in downstream analyses.

We plan the workshop to be an instructor-led live demo with time
for questions and interactions with the participants.

## Pre-requisites

* Basic knowledge of R syntax

## Workshop Participation

Students will participate by following along a live demo, and asking
questions or providing feedback throughout.

## _R_ / _Bioconductor_ packages used

- tximport
- tximeta
- SummarizedExperiment
- SingleCellExperiment

## Time outline

An example for a 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| alevin for droplet scRNA-seq | 15m  |
| importing counts into Bioc   | 10m  |
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

- run alevin, quantifying scRNA-seq reads to make a gene count matrix
- import scRNA-seq count data including genomic ranges
- import scRNA-seq from EMBL based on experiment id
- manipulate a SingleCellExperiment
- examine distributions of scRNA-seq counts
- examine uncertainty estimates for counts
