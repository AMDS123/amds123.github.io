---
layout: post
title: "Baseline Desensitizing In Translation Averaging"
date: 2019-01-03 08:05:24
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Bingbing Zhuang, Loong-Fah Cheong, Gim Hee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Many existing translation averaging algorithms are either sensitive to disparate camera baselines and have to rely on extensive preprocessing to improve the observed Epipolar Geometry graph, or if they are robust against disparate camera baselines, require complicated optimization to minimize the highly nonlinear angular error objective. In this paper, we carefully design a simple yet effective bilinear objective function, introducing a variable to perform the requisite normalization. The objective function enjoys the baseline-insensitive property of the angular error and yet is amenable to simple and efficient optimization by block coordinate descent, with good empirical performance. A rotation-assisted Iterative Reweighted Least Squares scheme is further put forth to help deal with outliers. We also contribute towards a better understanding of the behavior of two recent convex algorithms, LUD and Shapefit/kick, clarifying the underlying subtle difference that leads to the performance gap. Finally, we demonstrate that our algorithm achieves overall superior accuracies in benchmark dataset compared to state-of-theart methods, and is also several times faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00643](http://arxiv.org/abs/1901.00643)

##### PDF
[http://arxiv.org/pdf/1901.00643](http://arxiv.org/pdf/1901.00643)

