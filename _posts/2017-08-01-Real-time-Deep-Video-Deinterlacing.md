---
layout: post
title: "Real-time Deep Video Deinterlacing"
date: 2017-08-01 07:23:53
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Haichao Zhu, Xueting Liu, Xiangyu Mao, Tien-Tsin Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Interlacing is a widely used technique, for television broadcast and video recording, to double the perceived frame rate without increasing the bandwidth. But it presents annoying visual artifacts, such as flickering and silhouette "serration," during the playback. Existing state-of-the-art deinterlacing methods either ignore the temporal information to provide real-time performance but lower visual quality, or estimate the motion for better deinterlacing but with a trade-off of higher computational cost. In this paper, we present the first and novel deep convolutional neural networks (DCNNs) based method to deinterlace with high visual quality and real-time performance. Unlike existing models for super-resolution problems which relies on the translation-invariant assumption, our proposed DCNN model utilizes the temporal information from both the odd and even half frames to reconstruct only the missing scanlines, and retains the given odd and even scanlines for producing the full deinterlaced frames. By further introducing a layer-sharable architecture, our system can achieve real-time performance on a single GPU. Experiments shows that our method outperforms all existing methods, in terms of reconstruction accuracy and computational performance.

##### Abstract (translated by Google)
隔行扫描是广泛使用的技术，用于电视广播和视频录制，在不增加带宽的情况下将感知帧速率提高一倍。但在播放过程中会出现恼人的视觉伪影，如闪烁和轮廓“锯齿”。现有的最先进的去隔行方法要么忽略时间信息以提供实时性能，要么降低视觉质量，或者为了更好的去隔行而估计运动，但是要牺牲更高的计算成本。在本文中，我们提出了第一个和新的深度卷积神经网络（DCNNs）的方法，以高质量的视频和实时性能。与现有的依赖于平移不变假设的超分辨率问题的模型不同，我们提出的DCNN模型利用来自奇数和偶数半帧的时间信息来仅重建丢失的扫描线，并保留给定的奇数和偶数扫描线完全去隔行帧。通过进一步引入层可共享架构，我们的系统可以在单个GPU上实现实时性能。实验表明，该方法在重构精度和计算性能方面优于现有方法。

##### URL
[https://arxiv.org/abs/1708.00187](https://arxiv.org/abs/1708.00187)

##### PDF
[https://arxiv.org/pdf/1708.00187](https://arxiv.org/pdf/1708.00187)

