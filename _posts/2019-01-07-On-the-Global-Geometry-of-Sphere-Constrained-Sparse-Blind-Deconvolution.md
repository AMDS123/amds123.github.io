---
layout: post
title: "On the Global Geometry of Sphere-Constrained Sparse Blind Deconvolution"
date: 2019-01-07 16:42:46
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization
author: Yuqian Zhang, Yenson Lau, Han-Wen Kuo, Sky Cheung, Abhay Pasupathy, John Wright
mathjax: true
---

* content
{:toc}

##### Abstract
Blind deconvolution is the problem of recovering a convolutional kernel $\boldsymbol a_0$ and an activation signal $\boldsymbol x_0$ from their convolution $\boldsymbol y = \boldsymbol a_0 \circledast \boldsymbol x_0$. This problem is ill-posed without further constraints or priors. This paper studies the situation where the nonzero entries in the activation signal are sparsely and randomly populated. We normalize the convolution kernel to have unit Frobenius norm and cast the sparse blind deconvolution problem as a nonconvex optimization problem over the sphere. With this spherical constraint, every spurious local minimum turns out to be close to some signed shift truncation of the ground truth, under certain hypotheses. This benign property motivates an effective two stage algorithm that recovers the ground truth from the partial information offered by a suboptimal local minimum. This geometry-inspired algorithm recovers the ground truth for certain microscopy problems, also exhibits promising performance in the more challenging image deblurring problem. Our insights into the global geometry and the two stage algorithm extend to the convolutional dictionary learning problem, where a superposition of multiple convolution signals is observed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01913](http://arxiv.org/abs/1901.01913)

##### PDF
[http://arxiv.org/pdf/1901.01913](http://arxiv.org/pdf/1901.01913)

