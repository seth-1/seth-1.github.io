---
layout: default
title: Tutorials
---

# Why working with R?

Antismash is already providing many functions and analysis tools in it's web interface. However, projects often involve newly sequenced organisms that are not available in public databases yet and only owned by you. Therefore, you have to perform certain analyses on your own, including unpublished and non analysed data.

Learning R will also help you in handling the increasing  amount of data we are confronted with. Projects that work on 100 to 300 genomes at the same time are common and certain projects combine analyses of [1000 genomes](http://genome.jgi.doe.gov/programs/fungi/1000fungalgenomes.jsf).

![all genomes](https://cdn.meme.am/cache/instances/folder204/65722204.jpg)

So more data will become available and it will become increasingly important to work on these in a high throughput as well as reproducible manner.

# Data

We will use antismash outputs of 4 Aspergillus genomes to mine them for secondary metabolic gene clusters. Using R we will develop a high throughput method which helps us to compare multiple datasets containing large amounts of data and mining for natural products of interest.

## Reading data into R

```r
dat <- read.table("example.tsv", sep = '\t') # Reading example file
head(dat)                                    # Showing the header
str(dat)                                     # Overview of observations (rows) and variables (columns)
```

# Working with R
