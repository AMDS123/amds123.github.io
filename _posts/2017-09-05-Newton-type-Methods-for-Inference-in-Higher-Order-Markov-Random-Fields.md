---
layout: post
title: "Newton-type Methods for Inference in Higher-Order Markov Random Fields"
date: 2017-09-05 04:55:47
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Inference
author: Hariprasad Kannan, Nikos Komodakis, Nikos Paragios
mathjax: true
---

* content
{:toc}

##### Abstract
Linear programming relaxations are central to {\sc map} inference in discrete Markov Random Fields. The ability to properly solve the Lagrangian dual is a critical component of such methods. In this paper, we study the benefit of using Newton-type methods to solve the Lagrangian dual of a smooth version of the problem. We investigate their ability to achieve superior convergence behavior and to better handle the ill-conditioned nature of the formulation, as compared to first order methods. We show that it is indeed possible to efficiently apply a trust region Newton method for a broad range of {\sc map} inference problems. In this paper we propose a provably convergent and efficient framework that includes (i) excellent compromise between computational complexity and precision concerning the Hessian matrix construction, (ii) a damping strategy that aids efficient optimization, (iii) a truncation strategy coupled with a generic pre-conditioner for Conjugate Gradients, (iv) efficient sum-product computation for sparse clique potentials. Results for higher-order Markov Random Fields demonstrate the potential of this approach.

##### Abstract (translated by Google)
线性规划松弛是离散马尔科夫随机场中{\ sc map}推理的核心。适当解决拉格朗日对偶的能力是这种方法的关键组成部分。在本文中，我们研究了使用牛顿型方法解决平滑问题的拉格朗日对偶的好处。我们调查他们的能力，实现优越的收敛行为，并与一阶方法相比，更好地处理配方的病态性质。我们证明，确实有可能对广泛的{\ sc map}推理问题有效​​地应用一个信任域牛顿法。在本文中，我们提出了一个可证明的收敛性和高效的框架，其中包括（i）关于Hessian矩阵构造的计算复杂性和精度之间的优异折衷，（ii）帮助有效优化的阻尼策略，（iii）共轭梯度的预处理，（iv）稀疏集团电位的有效积和计算。高阶马尔可夫随机场的结果证明了这种方法的潜力。

##### URL
[https://arxiv.org/abs/1709.01237](https://arxiv.org/abs/1709.01237)

##### PDF
[https://arxiv.org/pdf/1709.01237](https://arxiv.org/pdf/1709.01237)

