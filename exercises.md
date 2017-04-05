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
* Write a function that shows you the results in a table

## Combining the sets

Create a combination of your secondary metabolite annotations and interpro annotations

* What are common columns between the two sets?
* What do interpro annotations tell you about a protein?
* What does your dataframe now represent?

## Case 1 PKS

In comparative genomics and genome mining we often want to compare proteins by their annotations. One way to get a general view on the secondary metabolites produced by your organisms is to characterize a certain class of metabolites by their domains. In the following exercise we will focus on PKSs and their domains to characterize the products of our organisms.

### Recap

You already know about the basic build of PKSs, i.e. 3 domains with initiating, elongating and terminating function.

Based on your background knowledge of PKSs:
* What is the minimum set of domains needed to synthesize a polyketide?
* What are optional domains which further **diversify** the polyketide?

<!-- <div class = "spec-hi" >
<p>You already know about the basic build of PKS. It needs 3 domains with initiating, elongating and terminating function.  </p>
<ul>
<li>What are the domains that serve the functions needed to synthesize a polyketide </li>
<li>What are optional domains which further diversify the polyketide</li>
</ul>
</div>
If the latter crashes use or looks weird use a paragraph element inside the container -->

### Data questions

* Inspect the dataframe. Which column contains information about domains? Can you identify domains belonging to PKSs?
* can you recognize domains you learned about which further modify a *simple* PKS product?
* Using subsetting, find all PKSs that contain a Methyltransferase.
* Provide a dataframe showing the sum of all PKS containing Methyltransferases for all organisms.
* Repeat the last two steps for another domains with special function inside PKSs.

## Case 2 Gene cluster similarity
