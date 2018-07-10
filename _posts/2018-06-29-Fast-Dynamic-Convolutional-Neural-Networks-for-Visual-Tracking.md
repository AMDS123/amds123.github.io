---
layout: post
title: "Fast Dynamic Convolutional Neural Networks for Visual Tracking"
date: 2018-06-29 06:30:18
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Zhiyan Cui, Na Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the existing tracking methods based on CNN(convolutional neural networks) are too slow for real-time application despite the excellent tracking accuracy compared with the traditional ones. In this paper, a fast dynamic visual tracking algorithm combining CNN based MDNet(Multi-Domain Network) and RoIAlign was developed. The major problem of MDNet also lies in the time efficiency. Considering the computational complexity of MDNet is mainly caused by the large amount of convolution operations, a RoIPool layer which could conduct the convolution over the whole image instead of each RoI was added to accelerate the calculation. With RoIPool employed, the computation speed has been increased but the tracking accuracy has dropped simultaneously. RoIPool could lose some positioning accuracy because it can not handle locations represented by floating numbers. So RoIAlign, instead of RoIPool, which can process floating numbers of locations by bilinear interpolation has been added to the network. The results show the target localization accuracy has been improved and it hardly increases the computational cost. These strategies can accelerate the processing and make it 5x faster than MDNet with very low impact on accuracy. The proposed algorithm has been evaluated on two benchmarks: OTB100 and VOT2016, on which high accuracy and speed have been obtained. The influence of the network structure and training data are also discussed with experiments.

##### Abstract (translated by Google)
尽管与传统的跟踪方法相比具有出色的跟踪精度，但大多数基于CNN（卷积神经网络）的现有跟踪方法对于实时应用来说太慢了。本文开发了一种结合基于CNN的MDNet（多域网络）和RoIAlign的快速动态视觉跟踪算法。 MDNet的主要问题还在于时间效率。考虑到MDNet的计算复杂性主要是由大量的卷积运算引起的，因此添加了可以在整个图像上进行卷积而不是每个RoI的RoIPool层来加速计算。使用RoIPool后，计算速度提高了，但跟踪精度同时下降。 RoIPool可能会失去一些定位精度，因为它无法处理由浮动数字表示的位置。因此RoIAlign，而不是RoIPool，可以通过双线性插值处理浮动数量的位置已添加到网络中。结果表明，目标定位精度得到了提高，几乎没有增加计算成本。这些策略可以加速处理并使其比MDNet快5倍，对准确性的影响非常小。所提出的算法已经在两个基准上进行了评估：OTB100和VOT2016，已经获得了高精度和高速度。还通过实验讨论了网络结构和训练数据的影响。

##### URL
[http://arxiv.org/abs/1807.03132](http://arxiv.org/abs/1807.03132)

##### PDF
[http://arxiv.org/pdf/1807.03132](http://arxiv.org/pdf/1807.03132)

