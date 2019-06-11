---
layout: post
title: "Optimal Transport Relaxations with Application to Wasserstein GANs"
date: 2019-06-07 20:01:56
categories: arXiv_CV
tags: arXiv_CV Regularization GAN Optimization
author: Saied Mahdian, Jose Blanchet, Peter Glynn
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a family of relaxations of the optimal transport problem which regularize the problem by introducing an additional minimization step over a small region around one of the underlying transporting measures. The type of regularization that we obtain is related to smoothing techniques studied in the optimization literature. When using our approach to estimate optimal transport costs based on empirical measures, we obtain statistical learning bounds which are useful to guide the amount of regularization, while maintaining good generalization properties. To illustrate the computational advantages of our regularization approach, we apply our method to training Wasserstein GANs. We obtain running time improvements, relative to current benchmarks, with no deterioration in testing performance (via FID). The running time improvement occurs because our new optimality-based threshold criterion reduces the number of expensive iterates of the generating networks, while increasing the number of actor-critic iterations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.03317](https://arxiv.org/abs/1906.03317)

##### PDF
[https://arxiv.org/pdf/1906.03317](https://arxiv.org/pdf/1906.03317)

