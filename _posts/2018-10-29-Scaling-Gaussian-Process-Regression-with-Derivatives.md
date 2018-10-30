---
layout: post
title: "Scaling Gaussian Process Regression with Derivatives"
date: 2018-10-29 17:51:54
categories: arXiv_AI
tags: arXiv_AI Face Optimization Prediction
author: David Eriksson, Kun Dong, Eric Hans Lee, David Bindel, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian processes (GPs) with derivatives are useful in many applications, including Bayesian optimization, implicit surface reconstruction, and terrain reconstruction. Fitting a GP to function values and derivatives at $n$ points in $d$ dimensions requires linear solves and log determinants with an ${n(d+1) \times n(d+1)}$ positive definite matrix -- leading to prohibitive $\mathcal{O}(n^3d^3)$ computations for standard direct methods. We propose iterative solvers using fast $\mathcal{O}(nd)$ matrix-vector multiplications (MVMs), together with pivoted Cholesky preconditioning that cuts the iterations to convergence by several orders of magnitude, allowing for fast kernel learning and prediction. Our approaches, together with dimensionality reduction, enables Bayesian optimization with derivatives to scale to high-dimensional problems and large evaluation budgets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12283](http://arxiv.org/abs/1810.12283)

##### PDF
[http://arxiv.org/pdf/1810.12283](http://arxiv.org/pdf/1810.12283)

