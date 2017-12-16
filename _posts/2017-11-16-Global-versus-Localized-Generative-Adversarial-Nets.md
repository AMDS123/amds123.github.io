---
layout: post
title: "Global versus Localized Generative Adversarial Nets"
date: 2017-11-16 10:53:53
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Guo-Jun Qi, Liheng Zhang, Hao Hu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel localized Generative Adversarial Net (GAN) to learn on the manifold of real data. Compared with the classic GAN that {\em globally} parameterizes a manifold, the Localized GAN (LGAN) uses local coordinate charts to parameterize distinct local geometry of how data points can transform at different locations on the manifold. Specifically, around each point there exists a {\em local} generator that can produce data following diverse patterns of transformations on the manifold. The locality nature of LGAN enables local generators to adapt to and directly access the local geometry without need to invert the generator in a global GAN. Furthermore, it can prevent the manifold from being locally collapsed to a dimensionally deficient tangent subspace by imposing an orthonormality prior between tangents. This provides a geometric approach to alleviating mode collapse at least locally on the manifold by imposing independence between data transformations in different tangent directions. We will also demonstrate the LGAN can be applied to train a robust classifier that prefers locally consistent classification decisions on the manifold, and the resultant regularizer is closely related with the Laplace-Beltrami operator. Our experiments show that the proposed LGANs can not only produce diverse image transformations, but also deliver superior classification performances.

##### Abstract (translated by Google)
在本文中，我们提出了一个新的局部生成对手网（GAN）来学习真实数据的多样性。与全局参数化流形的经典GAN相比，局部GAN（LGAN）使用局部坐标图来表征数据点在流形上不同位置如何变换的不同局部几何。具体来说，在每个点附近都有一个{\ em局部}生成器，可以根据流形上不同的变换模式生成数据。 LGAN的局部性使得本地发电机能够适应并直接访问局部几何，而不需要在全局GAN中反转发电机。此外，通过在正切之间施加正交性，可以防止歧管局部塌陷到尺寸不足的正切子空间。这提供了通过在不同的切线方向上进行数据变换之间的独立性来至少在局部上减少模式崩溃的几何方法。我们也将证明LGAN可以用来训练一个鲁棒的分类器，它更喜欢在流形上进行局部一致的分类决策，所得到的正则化子与Laplace-Beltrami算子密切相关。我们的实验表明，所提出的LGAN不仅能够产生不同的图像变换，而且还能提供更好的分类性能。

##### URL
[https://arxiv.org/abs/1711.06020](https://arxiv.org/abs/1711.06020)

##### PDF
[https://arxiv.org/pdf/1711.06020](https://arxiv.org/pdf/1711.06020)

