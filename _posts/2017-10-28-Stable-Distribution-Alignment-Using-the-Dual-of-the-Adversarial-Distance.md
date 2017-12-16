---
layout: post
title: "Stable Distribution Alignment Using the Dual of the Adversarial Distance"
date: 2017-10-28 02:28:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Gradient_Descent
author: Ben Usman, Kate Saenko, Brian Kulis
mathjax: true
---

* content
{:toc}

##### Abstract
Methods that align distributions by minimizing an adversarial distance between them have recently achieved impressive results. However, these approaches are difficult to optimize with gradient descent and they often do not converge well without careful hyperparameter tuning and proper initialization. We investigate whether turning the adversarial min-max problem into an optimization problem by replacing the maximization part with its dual improves the quality of the resulting alignment and explore its connections to Maximum Mean Discrepancy. Our empirical results suggest that using the dual formulation for the restricted family of linear discriminators results in a more stable convergence to a desirable solution when compared with the performance of a primal min-max GAN-like objective and an MMD objective under the same restrictions. We test our hypothesis on the problem of aligning two synthetic point clouds on a plane and on a real-image domain adaptation problem on digits. In both cases, the dual formulation yields an iterative procedure that gives more stable and monotonic improvement over time.

##### Abstract (translated by Google)
通过最小化它们之间的敌对距离来调整分布的方法最近取得了令人印象深刻的结果。然而，这些方法难以用梯度下降来优化，并且如果没有仔细的超参数调整和适当的初始化，它们通常不会很好地收敛。我们调查是否把敌对最小最大问题转化为最优化问题，用最大化部分代替最大化部分提高了对齐的质量，并探究其与最大平均偏差的关系。我们的实证结果表明，使用线性鉴别器的受限族的对偶方程，与原始最小最大类GAN目标和MMD目标在相同限制条件下的性能相比，可以更稳定地收敛到理想的解。我们测试我们关于在一个平面上对齐两个合成点云的问题以及在数字上的一个实际图像域适应问题的假设。在这两种情况下，双重配方产生了一个迭代过程，随着时间的推移，这个过程更加稳定和单调。

##### URL
[https://arxiv.org/abs/1707.04046](https://arxiv.org/abs/1707.04046)

##### PDF
[https://arxiv.org/pdf/1707.04046](https://arxiv.org/pdf/1707.04046)

