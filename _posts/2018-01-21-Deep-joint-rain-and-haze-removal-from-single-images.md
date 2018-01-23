---
layout: post
title: "Deep joint rain and haze removal from single images"
date: 2018-01-21 05:09:58
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Liang Shen, Zihan Yue, Quan Chen, Fan Feng, Jie Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Rain removal from a single image is a challenge which has been studied for a long time. In this paper, a novel convolutional neural network based on wavelet and dark channel is proposed. On one hand, we think that rain streaks correspond to high frequency component of the image. Therefore, haar wavelet transform is a good choice to separate the rain streaks and background to some extent. More specifically, the LL subband of a rain image is more inclined to express the background information, while LH, HL, HH subband tend to represent the rain streaks and the edges. On the other hand, the accumulation of rain streaks from long distance makes the rain image look like haze veil. We extract dark channel of rain image as a feature map in network. By increasing this mapping between the dark channel of input and output images, we achieve haze removal in an indirect way. All of the parameters are optimized by back-propagation. Experiments on both synthetic and real- world datasets reveal that our method outperforms other state-of- the-art methods from a qualitative and quantitative perspective.

##### Abstract (translated by Google)
从单一的图像去除雨水是一项长期研究的挑战。本文提出了一种基于小波和暗信道的卷积神经网络。一方面，我们认为雨痕对应于图像的高频分量。因此，Haar小波变换在一定程度上是分离雨痕和背景的较好选择。更具体地说，雨图像的LL子带更倾向于表示背景信息，而LH，HL，HH子带倾向于表示雨痕和边缘。另一方面，长距离的雨水积聚，使得雨水图像看起来像雾霾的面纱。在网络中提取雨图像的暗通道作为特征图。通过增加输入和输出图像的暗通道之间的映射，我们以间接的方式实现雾霾移除。所有参数都通过反向传播进行优化。对合成和现实世界的数据集进行的实验表明，我们的方法从定性和定量的角度来看，都优于其他最先进的方法。

##### URL
[https://arxiv.org/abs/1801.06769](https://arxiv.org/abs/1801.06769)

##### PDF
[https://arxiv.org/pdf/1801.06769](https://arxiv.org/pdf/1801.06769)

