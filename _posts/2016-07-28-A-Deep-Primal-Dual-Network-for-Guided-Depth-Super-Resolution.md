---
layout: post
title: "A Deep Primal-Dual Network for Guided Depth Super-Resolution"
date: 2016-07-28 18:49:55
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Optimization
author: Gernot Riegler, David Ferstl, Matthias Rüther, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel method to increase the spatial resolution of depth images. We combine a deep fully convolutional network with a non-local variational method in a deep primal-dual network. The joint network computes a noise-free, high-resolution estimate from a noisy, low-resolution input depth map. Additionally, a high-resolution intensity image is used to guide the reconstruction in the network. By unrolling the optimization steps of a first-order primal-dual algorithm and formulating it as a network, we can train our joint method end-to-end. This not only enables us to learn the weights of the fully convolutional network, but also to optimize all parameters of the variational method and its optimization procedure. The training of such a deep network requires a large dataset for supervision. Therefore, we generate high-quality depth maps and corresponding color images with a physically based renderer. In an exhaustive evaluation we show that our method outperforms the state-of-the-art on multiple benchmarks.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来增加深度图像的空间分辨率。我们将深度完全卷积网络与非局部变分方法结合在一个深度原始 - 双重网络中。联合网络从嘈杂的，低分辨率的输入深度图计算无噪声，高分辨率的估计。此外，高分辨率强度图像被用来指导网络中的重建。通过展开一阶原始 - 对偶算法的优化步骤并将其作为一个网络，我们可以对我们的联合方法进行端到端的训练。这不仅使我们能够学习完全卷积网络的权重，而且能够优化变分法的所有参数及其优化过程。训练这样一个深度的网络需要一个庞大的数据集进行监督。因此，我们使用基于物理的渲染器生成高质量的深度图和相应的彩色图像。在详尽的评估中，我们展示了我们的方法在多个基准测试中胜过最先进的测试。

##### URL
[https://arxiv.org/abs/1607.08569](https://arxiv.org/abs/1607.08569)

##### PDF
[https://arxiv.org/pdf/1607.08569](https://arxiv.org/pdf/1607.08569)

