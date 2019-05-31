---
layout: post
title: "Zeroth-Order Stochastic Alternating Direction Method of Multipliers for Nonconvex Nonsmooth Optimization"
date: 2019-05-29 21:10:14
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Classification
author: Feihu Huang, Shangqian Gao, Songcan Chen, Heng Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Alternating direction method of multipliers (ADMM) is a popular optimization tool for the composite and constrained problems in machine learning. However, in many machine learning problems such as black-box attacks and bandit feedback, ADMM could fail because the explicit gradients of these problems are difficult or infeasible to obtain. Zeroth-order (gradient-free) methods can effectively solve these problems due to that the objective function values are only required in the optimization. Recently, though there exist a few zeroth-order ADMM methods, they build on the convexity of objective function. Clearly, these existing zeroth-order methods are limited in many applications. In the paper, thus, we propose a class of fast zeroth-order stochastic ADMM methods (i.e., ZO-SVRG-ADMM and ZO-SAGA-ADMM) for solving nonconvex problems with multiple nonsmooth penalties, based on the coordinate smoothing gradient estimator. Moreover, we prove that both the ZO-SVRG-ADMM and ZO-SAGA-ADMM have convergence rate of $O(1/T)$, where $T$ denotes the number of iterations. In particular, our methods not only reach the best convergence rate $O(1/T)$ for the nonconvex optimization, but also are able to effectively solve many complex machine learning problems with multiple regularized penalties and constraints. Finally, we conduct the experiments of black-box binary classification and structured adversarial attack on black-box deep neural network to validate the efficiency of our algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12729](http://arxiv.org/abs/1905.12729)

##### PDF
[http://arxiv.org/pdf/1905.12729](http://arxiv.org/pdf/1905.12729)

