---
layout: post
title: "Plug-and-Play Unplugged: Optimization Free Reconstruction using Consensus Equilibrium"
date: 2017-12-18 21:31:40
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Gregery T. Buzzard, Stanley H. Chan, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
Regularized inversion methods for image reconstruction are used widely due to their tractability and their ability to combine physical sensor models with useful regularity criteria. Such methods were used in the recently developed Plug-and-Play prior method, which provides a framework to use advanced denoisers as regularizers in inversion. However, the need to formulate regularized inversion as the solution to an optimization problem limits the expressiveness of possible regularity conditions and the variety of provably convergent Plug-and-Play denoising operators. 
 In this paper, we introduce the idea of Consensus Equilibrium (CE), which generalizes regularized inversion to include a wide variety of regularity operators without the need for an optimization formulation. CE is based on the solution of a set of equilibrium equations that balance data fit and regularity. In CE, the problem of MAP estimation in regularized inversion is replaced by the problem of solving these equations, which can be approached in multiple ways. 
 The key contribution of CE is to provide a novel framework for fusing a wide variety of regularizing operators with physical sensor models, even for models and operators that are not expressible via optimization. We describe the derivation of the CE equations and prove that the solution of the CE equations generalizes the standard MAP estimate. 
 We also discuss algorithms for solving the CE equations, including a version of the Douglas-Rachford (DR)/ADMM algorithm with a novel form of preconditioning and Newton's method, both standard form and a Jacobian-free form. We illustrate the idea of consensus equilibrium on several examples, one using an array of convolutional neural network denoisers, none of which is tuned to match the noise level in a noisy image but which in consensus can achieve a better result than any of them individually.

##### Abstract (translated by Google)
图像重建的正则化反演方法由于其易处理性和将物理传感器模型与有用的规则标准相结合的能力而被广泛使用。最近开发的即插即用优先方法使用了这种方法，该方法提供了一个框架，使用先进的拒识分器作为正规化反演。然而，需要制定正则化反演作为优化问题的解决方案，限制了可能的规律性条件的表达性以及可能会聚的即插即用降噪算子的多样性。
 在本文中，我们引入了共识均衡（CE）的概念，它将正规化反演推广到包括各种规则算子，而不需要优化公式。 CE基于平衡数据拟合和规律性的一组平衡方程的解。在CE中，正则化反演中的MAP估计问题被求解这些方程的问题所取代，可以用多种方法来处理。
 CE的主要贡献是提供一个新颖的框架，将各种正则化算子与物理传感器模型融合，即使对于通过优化不能表达的模型和算子也是如此。我们描述CE方程的推导，证明CE方程的解推广了标准MAP估计。
 我们还讨论了用于求解CE方程的算法，其中包括Douglas-Rachford（DR）/ ADMM算法的一个版本，其具有新的预条件形式和牛顿法，既是标准形式又是无雅可比形式。我们用几个卷积神经网络分解器来说明共识均衡的概念，其中没有一个被调整为与噪声图像中的噪声水平相匹配，但是它们的共识可以获得比其中任何一个更好的结果。

##### URL
[http://arxiv.org/abs/1705.08983](http://arxiv.org/abs/1705.08983)

##### PDF
[http://arxiv.org/pdf/1705.08983](http://arxiv.org/pdf/1705.08983)

