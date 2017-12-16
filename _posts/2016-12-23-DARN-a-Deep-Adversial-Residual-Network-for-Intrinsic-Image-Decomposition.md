---
layout: post
title: "DARN: a Deep Adversial Residual Network for Intrinsic Image Decomposition"
date: 2016-12-23 08:20:10
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative
author: Louis Lettry, Kenneth Vanhoey, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep supervised learning method for intrinsic decomposition of a single image into its albedo and shading components. Our contributions are based on a new fully convolutional neural network that estimates absolute albedo and shading jointly. As opposed to classical intrinsic image decomposition work, it is fully data-driven, hence does not require any physical priors like shading smoothness or albedo sparsity, nor does it rely on geometric information such as depth. Compared to recent deep learning techniques, we simplify the architecture, making it easier to build and train. It relies on a single end-to-end deep sequence of residual blocks and a perceptually-motivated metric formed by two discriminator networks. We train and demonstrate our architecture on the publicly available MPI Sintel dataset and its intrinsic image decomposition augmentation. We additionally discuss and augment the set of quantitative metrics so as to account for the more challenging recovery of non scale-invariant quantities. Results show that our work outperforms the state of the art algorithms both on the qualitative and quantitative aspect, while training convergence time is reduced.

##### Abstract (translated by Google)
我们提出了一种新的深度监督学习方法，用于将单个图像内在分解为反照率和阴影分量。我们的贡献是基于一个新的完全卷积神经网络，共同估计绝对反照率和阴影。与经典的固有图像分解工作相比，它完全是数据驱动的，因此不需要像阴影平滑或反射率稀疏这样的物理先验，也不需要像深度这样的几何信息。与最近的深度学习技术相比，我们简化了架构，使其更易于构建和培训。它依赖于一个单一的端到端的深度残差块序列和一个由两个鉴别器网络构成的感知动机指标。我们在公开可用的MPI Sintel数据集及其内在图像分解增强上训练和演示我们的架构。我们另外讨论并增加了一套定量指标，以解决非尺度不变量更具挑战性的恢复问题。结果表明，我们的工作在定性和定量方面都优于现有算法，同时减少了训练收敛时间。

##### URL
[https://arxiv.org/abs/1612.07899](https://arxiv.org/abs/1612.07899)

##### PDF
[https://arxiv.org/pdf/1612.07899](https://arxiv.org/pdf/1612.07899)

