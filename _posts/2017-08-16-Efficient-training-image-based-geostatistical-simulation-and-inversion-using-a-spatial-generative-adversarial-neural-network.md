---
layout: post
title: "Efficient training-image based geostatistical simulation and inversion using a spatial generative adversarial neural network"
date: 2017-08-16 17:04:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Eric Laloy, Romain Hérault, Diederik Jacques, Niklas Linde
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic inversion within a multiple-point statistics framework is still computationally prohibitive for large-scale problems. To partly address this, we introduce and evaluate a new training-image based simulation and inversion approach for complex geologic media. Our approach relies on a deep neural network of the spatial generative adversarial network (SGAN) type. After training using a training image (TI), our proposed SGAN can quickly generate 2D and 3D unconditional realizations. A key feature of our SGAN is that it defines a (very) low-dimensional parameterization, thereby allowing for efficient probabilistic (or deterministic) inversion using state-of-the-art Markov chain Monte Carlo (MCMC) methods. A series of 2D and 3D categorical TIs is first used to analyze the performance of our SGAN for unconditional simulation. The speed at which realizations are generated makes it especially useful for simulating over large grids and/or from a complex multi-categorical TI. Subsequently, synthetic inversion case studies involving 2D steady-state flow and 3D transient hydraulic tomography are used to illustrate the effectiveness of our proposed SGAN-based probabilistic inversion. For the 2D case, the inversion rapidly explores the posterior model distribution. For the 3D case, the inversion recovers model realizations that fit the data close to the target level and visually resemble the true model well. Future work will focus on the inclusion of direct conditioning data and application to continuous TIs.

##### Abstract (translated by Google)
多点统计框架内的概率反演对于大规模问题在计算上仍然是禁止的。为了部分解决这个问题，我们介绍和评估了一种新的基于训练图像的复杂地质介质模拟和反演方法。我们的方法依赖于空间生成对抗网络（SGAN）类型的深度神经网络。在使用训练图像（TI）训练之后，我们提出的SGAN可以快速生成2D和3D无条件实现。我们的SGAN的一个关键特征是它定义了一个（非常）低维参数化，从而允许使用最先进的马尔可夫链蒙特卡罗（MCMC）方法进行高效的概率（或确定性）反演。首先使用一系列2D和3D分类TI来分析我们的SGAN的无条件模拟性能。生成实现的速度对于模拟大型网格和/或复杂的多分类TI是特别有用的。随后，使用二维稳态流动和三维瞬态液压层析成像的综合反演案例研究来说明我们提出的基于SGAN的概率反演的有效性。对于2D情况，反演快速地探索后验模型分布。对于3D情况，反演恢复适合接近目标水平的数据的模型实现，并且在视觉上类似于真实模型。未来的工作将侧重于将直接调节数据和应用纳入到连续的TI中。

##### URL
[https://arxiv.org/abs/1708.04975](https://arxiv.org/abs/1708.04975)

##### PDF
[https://arxiv.org/pdf/1708.04975](https://arxiv.org/pdf/1708.04975)

