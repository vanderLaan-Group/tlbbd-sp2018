+++
title = "Super Learning of densities with the `sl3` and `condensier` R packages"
description = "An examination of density estimation within the Super Learning framework"
author = "Nima Hejazi"
publishDate = "2018-02-28"
draft = false
weight = 8
+++

## Lab 9: Super Learning of Densities

Today, we'll continue our ongoing discussion of Super Learner, this time taking
a look at how to perform density estimation within this framework. Having
discussed the motivations behind density estimation, we'll jump right in to
considering how to optimally perform density estimation using cross-validation.
To make these ideas concrete, we'll walk through how to use the [`condensier` R
package](https://github.com/osofr/condensier) to perform density
estimation with arbitrary machine learning algorithms by using the
[`sl3`](https://github.com/tlverse/sl3) R package.

### Lab Materials

* [GitHub repo (source)](https://github.com/tlbbd-spring2018/lab_09)
* [nbviewer (static HTML)](http://nbviewer.jupyter.org/github/tlbbd-spring2018/lab_09/blob/master/lab_09.ipynb)
* [binder (live
   notebook)](https://mybinder.org/v2/gh/tlbbd-spring2018/lab_09/master)

---

