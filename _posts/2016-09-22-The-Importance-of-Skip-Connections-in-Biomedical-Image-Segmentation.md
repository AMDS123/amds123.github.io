---
layout: post
title: "The Importance of Skip Connections in Biomedical Image Segmentation"
date: 2016-09-22 20:14:09
categories: arXiv_CV
tags: arXiv_CV Review Segmentation CNN
author: Michal Drozdzal, Eugene Vorontsov, Gabriel Chartrand, Samuel Kadoury, Chris Pal
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the influence of both long and short skip connections on Fully Convolutional Networks (FCN) for biomedical image segmentation. In standard FCNs, only long skip connections are used to skip features from the contracting path to the expanding path in order to recover spatial information lost during downsampling. We extend FCNs by adding short skip connections, that are similar to the ones introduced in residual networks, in order to build very deep FCNs (of hundreds of layers). A review of the gradient flow confirms that for a very deep FCN it is beneficial to have both long and short skip connections. Finally, we show that a very deep FCN can achieve near-to-state-of-the-art results on the EM dataset without any further post-processing.

##### Abstract (translated by Google)
本文研究了完全卷积网络（FCN）上的长短跳过连接对生物医学图像分割的影响。在标准FCNs中，只使用长跳过连接来跳过从签约路径到扩展路径的特征，以恢复下采样过程中丢失的空间信息。为了构建非常深的FCN（数百层），我们通过添加短跳转连接来扩展FCN，类似于残余网络中引入的短跳转连接。对梯度流量的回顾证实，对于非常深的FCN，具有长跳跃和短跳跃连接是有利的。最后，我们展示一个非常深的FCN可以在EM数据集上获得接近最新的结果，而不需要任何进一步的后处理。

##### URL
[https://arxiv.org/abs/1608.04117](https://arxiv.org/abs/1608.04117)

##### PDF
[https://arxiv.org/pdf/1608.04117](https://arxiv.org/pdf/1608.04117)

