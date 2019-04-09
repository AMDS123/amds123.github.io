---
layout: post
title: "Convex-Concave Backtracking for Inertial Bregman Proximal Gradient Algorithms in Non-Convex Optimization"
date: 2019-04-06 21:59:02
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Mahesh Chandra Mukkamala, Peter Ochs, Thomas Pock, Shoham Sabach
mathjax: true
---

* content
{:toc}

##### Abstract
Backtracking line-search is an old yet powerful strategy for finding better step size to be used in proximal gradient algorithms. The main principle is to locally find a simple convex upper bound of the objective function, which in turn controls the step size that is used. In case of inertial proximal gradient algorithms, the situation becomes much more difficult and usually leads to very restrictive rules on the extrapolation parameter. In this paper, we show that the extrapolation parameter can be controlled by locally finding also a simple concave lower bound of the objective function. This gives rise to a double convex-concave backtracking procedure which allows for an adaptive and optimal choice of both the step size and extrapolation parameters. We apply this procedure to the class of inertial Bregman proximal gradient methods, and prove that any sequence generated converges globally to critical points of the function at hand. Numerical experiments on a number of challenging non-convex problems in image processing and machine learning were conducted and show the power of combining inertial step and double backtracking strategy in achieving improved performances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03537](http://arxiv.org/abs/1904.03537)

##### PDF
[http://arxiv.org/pdf/1904.03537](http://arxiv.org/pdf/1904.03537)

