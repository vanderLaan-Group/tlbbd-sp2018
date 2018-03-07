+++
title = "Nonparametric density estimation with the `condensier` R package"
description = "An examination of kernel density estimation"
author = "Nima Hejazi"
publishDate = "2018-02-28"
draft = false
weight = 8
+++

## Lab 7: Nonparametric Density Estimation

Today, we'll switch topics and begin a discussion on kernel density estimation
and nonparametric methods for estimating densities. We'll begin by thinking
about the motivations for kernel density estimation, including a brief review of
the relevant theory. To make these ideas concrete, we'll walk through how to use
the [`condensier` R package](https://github.com/osofr/condensier) to perform
density estimation by fitting generalized linear models at various discrete bins
over the support of the outcome of interest. This will set the stage for a
future discussion on Super Learning of densities.

### Lab Materials

* [GitHub repo (source)](https://github.com/tlbbd-spring2018/lab_07)
* [nbviewer (static HTML)](http://nbviewer.jupyter.org/github/tlbbd-spring2018/lab_07/blob/master/lab_07.ipynb)
* [binder (live
   notebook)](https://mybinder.org/v2/gh/tlbbd-spring2018/lab_07/master)

---
