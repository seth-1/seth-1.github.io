---
layout: default
title: Exercises
---

# Introduction

We will use antismash outputs of 4 Aspergillus genomes to mine them for secondary metabolic gene clusters. Using R we will develop a high throughput method which helps us to compare multiple datasets containing large amounts of data and mining for natural products of interest.

## Input

To tell Rstudio where you want to work copy the file path like below and execute it in Rstudio
```r
setwd("path/to/directory")
```

* Load the file sm_annotation.tsv into R
* Inspect your data, what are the variables?

## Overview

Create an overview of the secondary metabolism for all organisms.

* Choose an appropriate visualization for your data
* Why did you choose a certain geom for your plot?
* What does the plot tell you about secondary metabolism in the 4 species

## Combining the sets

Create a combination of your secondary metabolite annotations and interpro annotations

* What are common columns between the two sets?
* What do interpro annotations tell you about a protein?
* What does your dataframe now represent?

### Case 1 PKS

* What are regular domains inside PKSs?
* What are domains with special functions?
* Using subsetting, find all PKSs that contain a Methyltransferase.
* Provide a dataframe showing the sum of all PKS containing Methyltransferases for all organisms.
* Repeat the last two steps for another domains with special function inside PKSs.

## Similarity of clusters