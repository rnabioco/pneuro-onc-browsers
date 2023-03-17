---
title: Single-cell RNA-seq of childhood medulloblastoma
summary: "scRNA-seq of 28 childhood medulloblastoma samples"
tags: 
- Cell Atlases
date: "2020-08-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

weight: 2

image:
  focal_point: Smart

links:
  
- url: https://d33sxa6bpqwi51.cloudfront.net/
  name: UCSC Cell Browser 

- url: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE156053
  name: GEO dataset

- url: https://doi.org/10.1093/neuonc/noab135
  name: Publication
  
- url: https://doi.org/10.1101/2020.08.28.272021
  name: Preprint
  
- icon: github
  icon_pack: fab
  name: Analysis Code
  url: https://github.com/rnabioco/medulloblast
  


url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

We explored cellular heterogeneity in medulloblastoma (MB) using single-cell RNA sequencing (scRNA-seq), immunohistochemistry and deconvolution of bulk transcriptomic data. Over 45,000 cells from 28 patients from all main subgroups of medulloblastoma (1 WNT, 9 SHH, 7 GP3 and 11 GP4) were clustered using Harmony alignment to identify conserved subpopulations.  

Accompanies the [manuscript]({{< relref "/content/publication/Riemondy-2021-tg/index.md">}}) "Neoplastic and immune single cell transcriptomics define subgroup-specific intra-tumoral heterogeneity of childhood medulloblastoma"

## Data and code availability

scRNA-seq and methylation data have been deposited in the National Center for Biotechnology Information Gene Expression Omnibus (GEO) database. [GSE156053](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE156053)

A [UCSC cellbrowser](https://d33sxa6bpqwi51.cloudfront.net/) is available for interactive exploration of the data.

Analysis scripts (Rmarkdown) are hosted on github:  [`rnabioco/medulloblast`](https://github.com/rnabioco/medulloblast)

## Supported by

National Institutes of Health (R01 CA237608-01)   
Cancer League of Colorado (research grant AWD 173796-SV)   
Tanner Seebaum Foundation  
Morgan Adams Foundation  
University of Colorado’s NIH/NCI Cancer Center (P30CA046934)  
