+++
title = "Computing Targeted Maximum Likelihood Estimators"
description = "A general discussion of how to compute TML estimators"
author = "Nima Hejazi"
publishDate = "2018-04-18"
draft = false
weight = 14
+++

## Lab 13: Computing Targeted Maximum Likelihood Estimators

Today, we'll begin on the final topic of our lab sections:
Targeted Maximum Likelihood Estimators (TMLEs). After a quick and general review
of the key properties of TMLEs, we'll discuss how to construct these estimators,
and the several steps required to do so. To provide some substance to our
discussion, we'll focus on computing the TMLE for the Average Treatment Effect,
looking at how we could write fairly simple code to compute the relevant
estimator. To wrap up, we'll take a look at
[`tmle3`](https://github.com/jeremyrcoyle/tmle3), a recent R package that makes
the computation of TMLEs essentially trivial.

---
