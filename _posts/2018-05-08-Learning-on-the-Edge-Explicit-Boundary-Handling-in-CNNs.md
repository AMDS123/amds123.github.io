---
layout: post
title: "Learning on the Edge: Explicit Boundary Handling in CNNs"
date: 2018-05-08 15:29:17
categories: arXiv_CV
tags: arXiv_CV CNN
author: Carlo Innamorati, Tobias Ritschel, Tim Weyrich, Niloy J. Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) handle the case where filters extend beyond the image boundary using several heuristics, such as zero, repeat or mean padding. These schemes are applied in an ad-hoc fashion and, being weakly related to the image content and oblivious of the target task, result in low output quality at the boundary. In this paper, we propose a simple and effective improvement that learns the boundary handling itself. At training-time, the network is provided with a separate set of explicit boundary filters. At testing-time, we use these filters which have learned to extrapolate features at the boundary in an optimal way for the specific task. Our extensive evaluation, over a wide range of architectural changes (variations of layers, feature channels, or both), shows how the explicit filters result in improved boundary handling. Consequently, we demonstrate an improvement of 5% to 20% across the board of typical CNN applications (colorization, de-Bayering, optical flow, and disparity estimation).

##### Abstract (translated by Google)
卷积神经网络（CNN）处理滤波器使用多种启发式（例如零点，重复或平均填充）延伸到图像边界之外的情况。这些方案以特别的方式被应用，并且与图像内容弱相关并且不理解目标任务，导致边界处的输出质量低。在本文中，我们提出了一个简单而有效的改进来学习边界处理本身。在训练时，网络提供了一组单独的显式边界过滤器。在测试阶段，我们使用这些已经学会以特定任务的最佳方式在边界推断特征的滤波器。我们对广泛的架构变化（层数，特性通道或两者的变化）进行了广泛的评估，显示了显式过滤器如何改进边界处理。因此，我们展示了典型CNN应用（彩色化，去拜耳，光流和视差估计）的5％到20％的提高。

##### URL
[https://arxiv.org/abs/1805.03106](https://arxiv.org/abs/1805.03106)

##### PDF
[https://arxiv.org/pdf/1805.03106](https://arxiv.org/pdf/1805.03106)

