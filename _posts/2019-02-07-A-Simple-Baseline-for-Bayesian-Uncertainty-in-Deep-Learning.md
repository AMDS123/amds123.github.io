---
layout: post
title: "A Simple Baseline for Bayesian Uncertainty in Deep Learning"
date: 2019-02-07 05:15:46
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning Deep_Learning Detection Gradient_Descent
author: Wesley Maddox, Timur Garipov, Pavel Izmailov, Dmitry Vetrov, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
We propose SWA-Gaussian (SWAG), a simple, scalable, and general purpose approach for uncertainty representation and calibration in deep learning. Stochastic Weight Averaging (SWA), which computes the first moment of stochastic gradient descent (SGD) iterates with a modified learning rate schedule, has recently been shown to improve generalization in deep learning. With SWAG, we fit a Gaussian using the SWA solution as the first moment and a low rank plus diagonal covariance also derived from the SGD iterates, forming an approximate posterior distribution over neural network weights; we then sample from this Gaussian distribution to perform Bayesian model averaging. We empirically find that SWAG approximates the shape of the true posterior, in accordance with results describing the stationary distribution of SGD iterates. Moreover, we demonstrate that SWAG performs well on a wide variety of computer vision tasks, including out of sample detection, calibration, and transfer learning, in comparison to many popular alternatives including MC dropout, KFAC Laplace, and temperature scaling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02476](http://arxiv.org/abs/1902.02476)

##### PDF
[http://arxiv.org/pdf/1902.02476](http://arxiv.org/pdf/1902.02476)

