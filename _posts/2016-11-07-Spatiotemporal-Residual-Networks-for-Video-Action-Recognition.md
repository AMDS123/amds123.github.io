---
layout: post
title: "Spatiotemporal Residual Networks for Video Action Recognition"
date: 2016-11-07 16:17:16
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Christoph Feichtenhofer, Axel Pinz, Richard P. Wildes
mathjax: true
---

* content
{:toc}

##### Abstract
Two-stream Convolutional Networks (ConvNets) have shown strong performance for human action recognition in videos. Recently, Residual Networks (ResNets) have arisen as a new technique to train extremely deep architectures. In this paper, we introduce spatiotemporal ResNets as a combination of these two approaches. Our novel architecture generalizes ResNets for the spatiotemporal domain by introducing residual connections in two ways. First, we inject residual connections between the appearance and motion pathways of a two-stream architecture to allow spatiotemporal interaction between the two streams. Second, we transform pretrained image ConvNets into spatiotemporal networks by equipping these with learnable convolutional filters that are initialized as temporal residual connections and operate on adjacent feature maps in time. This approach slowly increases the spatiotemporal receptive field as the depth of the model increases and naturally integrates image ConvNet design principles. The whole model is trained end-to-end to allow hierarchical learning of complex spatiotemporal features. We evaluate our novel spatiotemporal ResNet using two widely used action recognition benchmarks where it exceeds the previous state-of-the-art.

##### Abstract (translated by Google)
双流卷积网络（ConvNets）在视频中的人体动作识别方面表现出色。最近，残余网络（ResNet）已经成为培养极其深厚架构的新技术。在本文中，我们引入了时空ResNets作为这两种方法的组合。我们的新架构通过两种方式引入剩余连接来将ResNets推广到时空域。首先，我们在双流架构的外观和运动路径之间注入剩余连接，以允许两个流之间的时空交互。其次，通过将预训练的图像ConvNets转换成时空网络，将它们与可学习的卷积滤波器相结合，这些卷积滤波器被初始化为时间的剩余连接，并及时在相邻的特征地图上进行操作。随着模型深度的增加，这种方法会缓慢增加时空感受域，并自然地将ConvNet的设计原理整合在一起。整个模型是端对端训练，允许复杂的时空特征的分层学习。我们使用两个广泛使用的动作识别基准来评估我们的新型时空ResNet，它超越了以前的先进水平。

##### URL
[https://arxiv.org/abs/1611.02155](https://arxiv.org/abs/1611.02155)

##### PDF
[https://arxiv.org/pdf/1611.02155](https://arxiv.org/pdf/1611.02155)

