---
layout: post
title: "Can Maxout Units Downsize Restoration Networks? - Single Image Super-Resolution Using Lightweight CNN with Maxout Units"
date: 2017-11-07 07:37:06
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge CNN Classification
author: Jae-Seok Choi, Munchurl Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Rectified linear units (ReLU) are well-known to be helpful in obtaining faster convergence and thus higher performance for many deep-learning-based applications. However, networks with ReLU tend to perform poorly when the number of filter parameters is constrained to a small number. To overcome it, in this paper, we propose a novel network utilizing maxout units (MU), and show its effectiveness on super-resolution (SR) applications. In general, the MU has been known to make the filter sizes doubled in generating the feature maps of the same sizes in classification problems. In this paper, we first reveal that the MU can even make the filter sizes halved in restoration problems thus leading to compaction of the network sizes. To show this, our SR network is designed without increasing the filter sizes with MU, which outperforms the state of the art SR methods with a smaller number of filter parameters. To the best of our knowledge, we are the first to incorporate MU into SR applications and show promising performance results. In MU, feature maps from a previous convolutional layer are divided into two parts along channels, which are then compared element-wise and only their max values are passed to a next layer. Along with some interesting properties of MU to be analyzed, we further investigate other variants of MU and their effects. In addition, while ReLU have a trouble for learning in networks with a very small number of convolutional filter parameters, MU do not. For SR applications, our MU-based network reconstructs high-resolution images with comparable quality compared to previous deep-learning-based SR methods, with lower filter parameters.

##### Abstract (translated by Google)
整流线性单元（ReLU）众所周知有助于获得更快的收敛性，从而提高许多基于深度学习的应用的性能。然而，当滤波器参数的数量被限制到少量时，具有ReLU的网络倾向于表现不佳。为了克服这个问题，本文提出了一种利用最大单位（MU）的新型网络，并展示了其在超分辨率（SR）应用中的有效性。一般来说，已知MU在分类问题中使滤波器尺寸加倍以生成相同尺寸的特征映射。在本文中，我们首先表明，MU甚至可以使滤波器的大小减半，从而导致网络尺寸的缩小。为了说明这一点，我们的SR网络在不增加MU的滤波器尺寸的情况下进行设计，这比使用较少的滤波器参数的现有SR方法的状态更好。就我们所知，我们是第一个将MU整合到SR应用程序中，并展现出良好的性能结果。在MU中，来自先前卷积层的特征图被沿着通道分成两部分，然后按照元素进行比较，并且只有它们的最大值被传递到下一层。除了要分析的MU的一些有趣的属性，我们进一步研究MU的其他变体及其影响。另外，虽然ReLU在卷积滤波器参数数量很少的网络中学习困难，但是MU不这样做。对于SR应用，我们的基于MU的网络与先前的基于深度学习的SR方法相比以较低的滤波器参数重构具有可比较的质量的高分辨率图像。

##### URL
[https://arxiv.org/abs/1711.02321](https://arxiv.org/abs/1711.02321)

##### PDF
[https://arxiv.org/pdf/1711.02321](https://arxiv.org/pdf/1711.02321)

