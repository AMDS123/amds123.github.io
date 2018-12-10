---
layout: post
title: "On Uncensored Mean First-Passage-Time Performance Experiments with Multiwalk in $mathbb{R}^p$: a New Stochastic Optimization Algorithm"
date: 2018-12-06 03:31:29
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Franc Brglez
mathjax: true
---

* content
{:toc}

##### Abstract
A rigorous empirical comparison of two stochastic solvers is important when one of the solvers is a prototype of a new algorithm such as multiwalk (MWA). When searching for global minima in $\mathbb{R}^p$, the key data structures of MWA include: $p$ rulers with each ruler assigned $m$ marks and a set of $p$ neighborhood matrices of size up to $m(m-2)$, where each entry represents absolute values of pairwise differences between $m$ marks. Before taking the next step, a controller links the tableau of neighborhood matrices and computes new and improved positions for each of the $m$ marks. The number of columns in each neighborhood matrix is denoted as the neighborhood radius $r_n \le m-2$. Any variant of the DEA (differential evolution algorithm) has an effective population neighborhood of radius not larger than 1. Uncensored first-passage-time performance experiments that vary the neighborhood radius of a MW-solver can thus be readily compared to existing variants of DE-solvers. The paper considers seven test cases of increasing complexity and demonstrates, under uncensored first-passage-time performance experiments: (1) significant variability in convergence rate for seven DE-based solver configurations, and (2) consistent, monotonic, and significantly faster rate of convergence for the MW-solver prototype as we increase the neighborhood radius from 4 to its maximum value.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03075](http://arxiv.org/abs/1812.03075)

##### PDF
[http://arxiv.org/pdf/1812.03075](http://arxiv.org/pdf/1812.03075)

