---
layout: post
title: "Towards Unified Acceleration of High-Order Algorithms under Hölder Continuity and Uniform Convexity"
date: 2019-06-03 05:27:59
categories: arXiv_AI
tags: arXiv_AI Optimization Classification
author: Chaobing Song, Yi Ma
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, through a very intuitive {\em vanilla proximal method} perspective, we derive accelerated high-order optimization algorithms for minimizing a convex function that has Hölder continuous derivatives. In this general convex setting, we propose a {\em unified acceleration algorithm} with an iteration complexity that matches the lower iteration complexity bound given in \cite{grapiglia2019tensor}. If the function is further uniformly convex, we propose a {\em general restart scheme}. The iteration complexity of the algorithm matches existing lower bounds in most important cases. For practical implementation, we introduce a new and effective heuristic that significantly simplifies the binary search procedure required by the algorithm, which makes the algorithm in general settings as efficient as the special case \cite{grapiglia2019tensor}. On large-scale classification datasets, our algorithm demonstrates clear and consistent advantages of high-order acceleration methods over first-order ones, in terms of run-time complexity. Our formulation considers the more general composite setting in which the objective function may contain a second possibly non-smooth convex term. Our analysis and proofs are also applicable to the general case in which the high-order smoothness conditions are with respect to non-Euclidean norms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.00582](https://arxiv.org/abs/1906.00582)

##### PDF
[https://arxiv.org/pdf/1906.00582](https://arxiv.org/pdf/1906.00582)

