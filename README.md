# Fluent genomic data analyses with plyranges and tximeta

# Instructor(s) name(s) and contact information

- Michael Love (michaelisaiahlove at gmail dot com)
- Michael Lawrence (lawrence.michael at gene dot com)
- Stuart Lee (co-author)

# Workshop Description

In this workshop, we will explore data from one or two experiments, 
where we are interested in intersecting epigenetic data (ChIP-seq or 
ATAC-seq peaks) with transcriptomic data (RNA-seq gene or transcript 
expression). We will demonstrate how to read in RNA-seq data in such 
a way that correct genomic ranges are automatically added to a rich 
Bioconductor data object. We will then show how to use the plyranges 
package, which provides "verbs" for genomic range manipulation and 
computation in a similar manner to the dplyr package for data frames.

We plan the workshop to be an instructor-led live demo with time
for questions and interactions with the participants.

## Pre-requisites

* Basic knowledge of R syntax

## Workshop Participation

Students will participate by following along a live demo, and asking
questions or providing feedback throughout.

## _R_ / _Bioconductor_ packages used

- plyranges
- tximeta
- SummarizedExperiment
- DESeq2
- limma

## Time outline

An example for a 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| tximeta: importing RNA-seq   | 10m  |
| importing peaks              | 10m  |
| plyrange introduction        | 10m  |
| intersecting peaks and genes | 15m  |

# Workshop goals and objectives

## Learning goals

- understand how to formulate genomic analyses using plyranges "verbs"
- describe how Bioconductor facilitates reproducible workflows 
  for genomic data anlaysis

## Learning objectives

- import RNA-seq data including genomic ranges
- manipulate a SummarizedExperiment
- overlap ChIP- or ATAC-seq peaks and gene expression with plyranges
- produce enrichment plots
