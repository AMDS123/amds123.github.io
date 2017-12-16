---
layout: post
title: "Plug-and-Play Unplugged: Optimization Free Reconstruction using Consensus Equilibrium"
date: 2017-05-24 22:27:00
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Gregery T. Buzzard, Suhas Sreehari, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
Regularized inversion methods for image reconstruction are used widely due to their tractability and their ability to combine complex physical sensor models with useful regularity criteria. Such methods were used in the recently developed Plug-and-Play prior method, which provides a framework to use advanced denoising algorithms as regularizers in inversion. However, the need to formulate regularized inversion as the solution to an optimization problem severely limits both the expressiveness of possible regularity conditions and the variety of provably convergent Plug-and-Play denoising operators. In this paper, we introduce the concept of consensus equilibrium (CE), which generalizes regularized inversion to include a much wider variety of regularity operators without the need for an optimization formulation. Consensus equilibrium is based on the solution of a set of equilibrium equations that balance data fit and regularity. In this framework, the problem of MAP estimation in regularized inversion is replaced by the problem of solving these equilibrium equations, which can be approached in multiple ways, including as a fixed point problem that generalizes the ADMM approach used in the Plug-and-Play method. We present the Douglas-Rachford (DR) algorithm for computing the CE solution as a fixed point and prove the convergence of this algorithm under conditions that include denoising operators that do not arise from optimization problems and that may not be nonexpansive. We give several examples to illustrate the idea of consensus equilibrium and the convergence properties of the DR algorithm and demonstrate this method on a sparse interpolation problem using electron microscopy data.

##### Abstract (translated by Google)
图像重建的正则化反演方法由于其易处理性和将复杂的物理传感器模型与有用的规则标准相结合的能力而被广泛使用。最近开发的即插即用优先方法使用了这种方法，该方法提供了一个框架，使用先进的去噪算法作为正则化反演。然而，需要制定正则化反演作为优化问题的解决方案，严重限制了可能的规律性条件的表达性以及可能会聚的即插即用降噪算子的多样性。在本文中，我们引入共识均衡（CE）的概念，它将正规化反演推广到更广泛的规则运算符而不需要优化公式。共识均衡是基于平衡数据拟合和规律性的一组平衡方程的解。在这个框架下，正则化反演中的MAP估计问题被求解这些平衡方程的问题所取代，这个问题可以用多种方式来处理，包括作为一个固定点问题来推广即插即用中使用的ADMM方法方法。我们提出用于计算CE解决方案的Douglas-Rachford（DR）算法作为一个固定点，并且证明了这个算法在包含去噪算子的条件下的收敛性，这个算子不是由优化问题产生的，也可能不是非扩张的。我们给出了几个例子来说明一致均衡的思想和DR算法的收敛性质，并用电子显微镜数据证明了这种方法在稀疏插值问题上的效果。

##### URL
[https://arxiv.org/abs/1705.08983](https://arxiv.org/abs/1705.08983)

##### PDF
[https://arxiv.org/pdf/1705.08983](https://arxiv.org/pdf/1705.08983)

