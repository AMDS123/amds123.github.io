---
layout: post
title: "Application of Multi-channel 3D-cube Successive Convolution Network for Convective Storm Nowcasting"
date: 2017-03-02 11:04:17
categories: arXiv_CV
tags: arXiv_CV Attention CNN Deep_Learning
author: Wei Zhang, Lei Han, Juanzhen Sun, Hanyang Guo, Jie Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Convective storm nowcasting has attracted substantial attention in various fields. Existing methods under a deep learning framework rely primarily on radar data. Although they perform nowcast storm advection well, it is still challenging to nowcast storm initiation and growth, due to the limitations of the radar observations. This paper describes the first attempt to nowcast storm initiation, growth, and advection simultaneously under a deep learning framework using multi-source meteorological data. To this end, we present a multi-channel 3D-cube successive convolution network (3D-SCN). As real-time re-analysis meteorological data can now provide valuable atmospheric boundary layer thermal dynamic information, which is essential to predict storm initiation and growth, both raw 3D radar and re-analysis data are used directly without any handcraft feature engineering. These data are formulated as multi-channel 3D cubes, to be fed into our network, which are convolved by cross-channel 3D convolutions. By stacking successive convolutional layers without pooling, we build an end-to-end trainable model for nowcasting. Experimental results show that deep learning methods achieve better performance than traditional extrapolation methods. The qualitative analyses of 3D-SCN show encouraging results of nowcasting of storm initiation, growth, and advection.

##### Abstract (translated by Google)
对流风暴临近预报引起了各个领域的广泛关注。在深度学习框架下的现有方法主要依靠雷达数据。尽管它们能很好地进行临近风暴的平流，但是由于雷达观测的局限性，即时风暴的发生和增长仍然具有挑战性。本文描述了在多源气象资料的深度学习框架下同时实现风暴萌发，增长和平流的第一次尝试。为此，我们提出了一个多通道3D立方连续卷积网络（3D-SCN）。由于实时再分析气象数据现在可以提供有价值的大气边界层热动态信息，这对于预测风暴的起始和增长是必不可少的，原始3D雷达和重新分析数据都可以直接使用，而无需任何手工特征工程。这些数据被制定为多通道3D立方体，被馈送到我们的网络中，通过交叉通道3D卷积进行卷积。通过堆叠连续的卷积层而没有汇集，我们为临近预报建立一个端到端的可训练模型。实验结果表明，深度学习方法比传统的外推方法具有更好的性能。 3D-SCN的定性分析显示，风暴起始，成长和平流的临近预报结果令人鼓舞。

##### URL
[https://arxiv.org/abs/1702.04517](https://arxiv.org/abs/1702.04517)

##### PDF
[https://arxiv.org/pdf/1702.04517](https://arxiv.org/pdf/1702.04517)

