---
layout: post
title: "A HMAX with LLC for visual recognition"
date: 2015-02-11 04:40:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Transfer_Learning Optimization Detection Recognition
author: Kean Hong Lau, Yong Haur Tay, Fook Loong Lo
mathjax: true
---

* content
{:toc}

##### Abstract
Today's high performance deep artificial neural networks (ANNs) rely heavily on parameter optimization, which is sequential in nature and even with a powerful GPU, would have taken weeks to train them up for solving challenging tasks [22]. HMAX [17] has demonstrated that a simple high performing network could be obtained without heavy optimization. In this paper, we had improved on the existing best HMAX neural network [12] in terms of structural simplicity and performance. Our design replaces the L1 minimization sparse coding (SC) with a locality-constrained linear coding (LLC) [20] which has a lower computational demand. We also put the simple orientation filter bank back into the front layer of the network replacing PCA. Our system's performance has improved over the existing architecture and reached 79.0% on the challenging Caltech-101 [7] dataset, which is state-of-the-art for ANNs (without transfer learning). From our empirical data, the main contributors to our system's performance include an introduction of partial signal whitening, a spot detector, and a spatial pyramid matching (SPM) [14] layer.

##### Abstract (translated by Google)
如今的高性能深度人工神经网络（ANN）在很大程度上依赖于参数优化，而参数优化本质上是连续的，即使是强大的GPU，也需要花费数周的时间来训练它们以解决具有挑战性的任务[22]。 HMAX [17]已经证明，一个简单的高性能网络可以在没有大量优化的情况下获得。在本文中，我们已经在结构简单性和性能方面对现有的最佳HMAX神经网络[12]进行了改进。我们的设计取代了L1最小化稀疏编码（SC）与局部约束线性编码（LLC）[20]，其具有较低的计算需求。我们还把简单的方向滤波器组更换回网络的前一层，替换PCA。我们的系统性能比现有的架构有所提高，并且在具有挑战性的Caltech-101 [7]数据集中达到了79.0％，这是人工神经网络（无需转移学习）的最新技术。从我们的经验数据来看，我们系统性能的主要贡献者包括部分信号白化的介绍，点探测器和空间金字塔匹配（SPM）[14]层。

##### URL
[https://arxiv.org/abs/1502.02772](https://arxiv.org/abs/1502.02772)

##### PDF
[https://arxiv.org/pdf/1502.02772](https://arxiv.org/pdf/1502.02772)

