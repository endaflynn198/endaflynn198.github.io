---
layout: post
title: R Package for HDI Indicators
date: 2024-07-14 00:00:00
description: A new R package for analysing UN Human Development Indicators
tags: update
categories: code r package
---

# Learning to Build an R Package
The last few weeks I've learned how to build an R package. While I've been using R extensively for a while (almost a decade...), I've only built packages in Python before.

At the beginning of the process, I was frustrated with some of the quirks of R package building. However, with a bit more experience, I've come to see the benefits of helpers like `devtools`,`usethis`, and `roxygen2`.

Maybe in future I'll write a post on how to build an R package from scratch. But for now, I've provided [Resources](#resources) below which I found useful.

## The Data - HDI Indicators
The UN Human Development Indicators dataset encompasses a broad range of data that reflect the multi-dimensional aspects of human development across countries. These indicators offer insights into the health, education levels, and economic status of different populations, providing a comprehensive understanding of global human development trends.

You can find the data [here](https://data.humdata.org/dataset/?organization=undp-human-development-reports-office&q=Human+Development+Indicators).

## The Package
The package I've built is designed to allow the easy summary and comparison of UN Human Development Indicators data.

While it's somewhat basic (as it's more of a learning exercise), it does offer some useful functions for summarising and comparing the data between different countries. And, of course, being an R package it can be easily extended to include more functionality in future.

You can install it from GitHub using the following code:

```r
devtools::install_github("endaflynn198/HDI_summary")
library(HDIsummary)
```

And you can get a sense of the package by reading the vignette comparing Singapore and Nigeria [here](https://htmlpreview.github.io/?https://github.com/endaflynn198/HDI_summary/blob/main/vignettes/HDIsummary.html).

> Note that the above link makes use of GitHub's HTML previewer which you can find [here](https://htmlpreview.github.io/). I highly recommend it for sharing HTML files in your GitHub repositories as GitHub doesn't render them directly.

## Resources
If you're interested in learning more about building R packages, I recommend the following resources:
1. [R Packages by Hadley Wickham and Jennifer Bryan](https://r-pkgs.org/)
2. [RStudio's Package Development Cheat Sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/package-development.pdf)

## Soundtrack
While building this package I've been listening to a lot of [The Four Freshmen](https://www.youtube.com/watch?v=0N0QVRWWt6g) - a harmonic highlight of an old favourite is at 3.10 of the linked video. Soothing when you're trying to figure out why your package isn't building properly or restarting your R session for the 10th time...

