---
layout: post
title: "When is a Convolutional Filter Easy To Learn?"
date: 2017-09-18 19:09:24
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Gradient_Descent
author: Simon S. Du, Jason D. Lee, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze the convergence of (stochastic) gradient descent algorithm for learning a convolutional filter with Rectified Linear Unit (ReLU) activation function. Our analysis does not rely on any specific form of the input distribution and our proofs only use the definition of ReLU, in contrast with previous works that are restricted to standard Gaussian input. We show that (stochastic) gradient descent with random initialization can learn the convolutional filter in polynomial time and the convergence rate depends on the smoothness of the input distribution and the closeness of patches. To the best of our knowledge, this is the first recovery guarantee of gradient-based algorithms for convolutional filter on non-Gaussian input distributions. Our theory also justifies the two-stage learning rate strategy in deep neural networks. While our focus is theoretical, we also present experiments that illustrate our theoretical findings.

##### Abstract (translated by Google)
我们分析了（随机）梯度下降算法的收敛性，用于学习具有整数线性单元（ReLU）激活函数的卷积滤波器。我们的分析不依赖于输入分布的任何特定形式，我们的证明仅使用ReLU的定义，与以前的作品仅限于标准的高斯输入相比。我们证明随机初始化（随机）梯度下降可以在多项式时间学习卷积滤波器，收敛速度取决于输入分布的平滑性和贴片的贴近性。就我们所知，这是非高斯输入分布上的卷积滤波器的基于梯度的算法的首次恢复保证。我们的理论也证明了深度神经网络中的两阶段学习率策略。虽然我们的重点是理论上的，但我们也提供实验来说明我们的理论发现。

##### URL
[https://arxiv.org/abs/1709.06129](https://arxiv.org/abs/1709.06129)

##### PDF
[https://arxiv.org/pdf/1709.06129](https://arxiv.org/pdf/1709.06129)

