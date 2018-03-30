---
layout: post
title: "Cascaded multi-scale and multi-dimension convolutional neural network for stereo matching"
date: 2018-03-26 06:51:46
categories: arXiv_CV
tags: arXiv_CV CNN
author: Haihua Lu, Hai Xu, Li Zhang, Yong Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks(CNN) have been shown to perform better than the conventional stereo algorithms for stereo estimation. Numerous efforts focus on the pixel-wise matching cost computation, which is the important building block for many start-of-the-art algorithms. However, those architectures are limited to small and single scale receptive fields and use traditional methods for cost aggregation or even ignore cost aggregation. Differently we take them both into consideration. Firstly, we propose a new multi-scale matching cost computation sub-network, in which two different sizes of receptive fields are implemented parallelly. In this way, the network can make the best use of both variants and balance the trade-off between the increase of receptive field and the loss of detail. Furthermore, we show that our multi-dimension aggregation sub-network which containing 2D convolution and 3D convolution operations can provide rich context and semantic information for estimating an accurate initial disparity. Finally, experiments on challenging stereo benchmark KITTI demonstrate that the proposed method can achieve competitive results even without any additional post-processing.

##### Abstract (translated by Google)
卷积神经网络（CNN）已被证明比立体声估计的传统立体声算法更好。许多努力都集中在逐像素匹配成本计算上，这是许多最先进算法的重要组成部分。然而，这些体系结构仅限于小型和单一规模的接受域，并使用传统方法进行成本聚合，甚至忽略成本聚合。不同的是，我们将它们都考虑在内。首先，我们提出了一个新的多尺度匹配成本计算子网络，其中两个不同大小的接受域并行实现。通过这种方式，网络可以充分利用这两种变体，并平衡接受领域增加和细节丢失之间的平衡。此外，我们表明，我们的包含二维卷积和三维卷积运算的多维聚合子网络可以提供丰富的上下文和语义信息来估计准确的初始视差。最后，对具有挑战性的立体声基准KITTI的实验表明，即使没有任何额外的后处理，所提出的方法也可以实现竞争结果。

##### URL
[https://arxiv.org/abs/1803.09437](https://arxiv.org/abs/1803.09437)

##### PDF
[https://arxiv.org/pdf/1803.09437](https://arxiv.org/pdf/1803.09437)

