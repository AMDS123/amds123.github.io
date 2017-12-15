---
layout: post
title: "Robust Visual Tracking via Convolutional Networks"
date: 2015-08-24 06:07:22
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking CNN
author: Kaihua Zhang, Qingshan Liu, Yi Wu, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks have been successfully applied to visual tracking by learning a generic representation offline from numerous training images. However the offline training is time-consuming and the learned generic representation may be less discriminative for tracking specific objects. In this paper we present that, even without offline training with a large amount of auxiliary data, simple two-layer convolutional networks can be powerful enough to develop a robust representation for visual tracking. In the first frame, we employ the k-means algorithm to extract a set of normalized patches from the target region as fixed filters, which integrate a series of adaptive contextual filters surrounding the target to define a set of feature maps in the subsequent frames. These maps measure similarities between each filter and the useful local intensity patterns across the target, thereby encoding its local structural information. Furthermore, all the maps form together a global representation, which is built on mid-level features, thereby remaining close to image-level information, and hence the inner geometric layout of the target is also well preserved. A simple soft shrinkage method with an adaptive threshold is employed to de-noise the global representation, resulting in a robust sparse representation. The representation is updated via a simple and effective online strategy, allowing it to robustly adapt to target appearance variations. Our convolution networks have surprisingly lightweight structure, yet perform favorably against several state-of-the-art methods on the CVPR2013 tracking benchmark dataset with 50 challenging videos.

##### Abstract (translated by Google)
深度网络已成功应用于视觉跟踪，通过从众多训练图像中离线学习通用表示。然而，离线训练是耗时的，并且所学习的通用表示对于跟踪特定对象而言可能较不区分。在本文中，我们提出，即使没有大量的辅助数据的离线训练，简单的双层卷积网络可以足够强大，以开发视觉跟踪的鲁棒表示。在第一帧中，我们使用k均值算法从目标区域提取一组归一化的块作为固定的滤波器，这些滤波器集成了围绕目标的一系列自适应上下文滤波器，以在后续帧中定义一组特征映射。这些地图测量每个过滤器与整个目标的有用局部强度模式之间的相似性，从而编码其本地结构信息。此外，所有的地图一起构成了一个全局的表示，它是建立在中间层次的特征上的，因此保持接近图像层次的信息，因此目标的内部几何布局也得到了很好的保留。采用具有自适应阈值的简单软收缩方法对全局表示进行去噪，从而得到鲁棒的稀疏表示。该表示通过简单有效的在线策略进行更新，使其能够适应目标的外观变化。我们的卷积网络具有令人惊讶的轻量级结构，但是在CVPR2013跟踪基准数据集上有几个最先进的方法，并具有5​​0个具有挑战性的视频。

##### URL
[https://arxiv.org/abs/1501.04505](https://arxiv.org/abs/1501.04505)

##### PDF
[https://arxiv.org/pdf/1501.04505](https://arxiv.org/pdf/1501.04505)

