---
layout: post
title: "DARN: a Deep Adversial Residual Network for Intrinsic Image Decomposition"
date: 2018-03-20 11:05:57
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Deep_Learning Quantitative
author: Louis Lettry, Kenneth Vanhoey, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep supervised learning method for intrinsic decomposition of a single image into its albedo and shading components. Our contributions are based on a new fully convolutional neural network that estimates absolute albedo and shading jointly. Our solution relies on a single end-to-end deep sequence of residual blocks and a perceptually-motivated metric formed by two adversarially trained discriminators. As opposed to classical intrinsic image decomposition work, it is fully data-driven, hence does not require any physical priors like shading smoothness or albedo sparsity, nor does it rely on geometric information such as depth. Compared to recent deep learning techniques, we simplify the architecture, making it easier to build and train, and constrain it to generate a valid and reversible decomposition. We rediscuss and augment the set of quantitative metrics so as to account for the more challenging recovery of non scale-invariant quantities. We train and demonstrate our architecture on the publicly available MPI Sintel dataset and its intrinsic image decomposition, show attenuated overfitting issues and discuss generalizability to other data. Results show that our work outperforms the state of the art deep algorithms both on the qualitative and quantitative aspect.

##### Abstract (translated by Google)
我们提出了一种新的深度监督学习方法，用于将单个图像内在分解为反照率和阴影分量。我们的贡献基于一个新的完全卷积神经网络，它可以共同估计绝对反照率和阴影。我们的解决方案依赖于单个端到端的深度序列残差块和由两个对手训练的鉴别器形成的感知动机指标。与经典的固有图像分解工作相反，它完全是数据驱动的，因此不需要像阴影平滑或反照率稀疏这样的物理先验，也不需要像深度这样的几何信息。与最近的深度学习技术相比，我们简化了架构，使构建和训练变得更加容易，并将其约束为生成有效且可逆的分解。我们重新检验并扩充了一套量化指标，以解决非尺度不变量更具挑战性的恢复问题。我们在公开可用的MPI Sintel数据集及其内在图像分解上训练和演示我们的架构，显示衰减的过度拟合问题并讨论其他数据的一般性。结果表明，我们的工作在定性和定量方面均优于最先进的深度算法。

##### URL
[http://arxiv.org/abs/1612.07899](http://arxiv.org/abs/1612.07899)

##### PDF
[http://arxiv.org/pdf/1612.07899](http://arxiv.org/pdf/1612.07899)

