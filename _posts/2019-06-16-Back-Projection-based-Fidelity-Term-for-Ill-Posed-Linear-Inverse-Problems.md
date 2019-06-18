---
layout: post
title: "Back-Projection based Fidelity Term for Ill-Posed Linear Inverse Problems"
date: 2019-06-16 23:27:37
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Tom Tirer, Raja Giryes
mathjax: true
---

* content
{:toc}

##### Abstract
Ill-posed linear inverse problems appear in many image processing applications, such as deblurring, super-resolution and compressed sensing. Many restoration strategies involve minimizing a cost function, which is composed of fidelity and prior terms, balanced by a regularization parameter. While a vast amount of research has been focused on different prior models, the fidelity term is almost always chosen to be the least squares (LS) objective, that encourages fitting the linearly transformed optimization variable to the observations. In this work, we examine a different fidelity term, which has been implicitly used by the recently proposed iterative denoising and backward projections (IDBP) framework. This term encourages agreement between the projection of the optimization variable onto the row space of the linear operator and the pseudo-inverse of the linear operator ("back-projection") applied on the observations. We analytically examine the difference between the two fidelity terms for Tikhonov regularization and identify cases where the new term has an advantage over the standard LS one. Moreover, we demonstrate empirically that the behavior of the two induced cost functions for sophisticated convex and non-convex priors, such as total-variation, BM3D, and deep generative models, correlates with the obtained theoretical analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06794](http://arxiv.org/abs/1906.06794)

##### PDF
[http://arxiv.org/pdf/1906.06794](http://arxiv.org/pdf/1906.06794)

