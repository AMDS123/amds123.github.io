---
layout: post
title: "Towards real-time unsupervised monocular depth estimation on CPU"
date: 2018-06-29 14:18:24
categories: arXiv_CV
tags: arXiv_CV Knowledge Deep_Learning
author: Matteo Poggi, Filippo Aleotti, Fabio Tosi, Stefano Mattoccia
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised depth estimation from a single image is a very attractive technique with several implications in robotic, autonomous navigation, augmented reality and so on. This topic represents a very challenging task and the advent of deep learning enabled to tackle this problem with excellent results. However, these architectures are extremely deep and complex. Thus, real-time performance can be achieved only leveraging on power-hungry GPUs that do not allow to infer depth maps in application fields characterized by low-power constraints. To tackle this issue, in this paper we propose a novel architecture capable to quickly infer an accurate depth map on a CPU, even of an embedded system, using a pyramid of features extracted from a single input image. Similarly to stateof-the-art, we train our network in an unsupervised manner casting depth estimation as an image reconstruction problem. Extensive experimental results on the KITTI 2015 dataset show that compared to the top performing approach our network has similar accuracy but a much lower complexity (about 6% of parameters) enabling to infer a depth map for a KITTI image in about 1.7 s on the Raspberry Pi 3 and at more than 8 Hz on a standard CPU. Moreover, by trading accuracy for efficiency, our network allows to infer maps at more than 2 Hz and 40 Hz respectively, still being more accurate than most state-of-the-art slower methods. To the best of our knowledge, it is the first method enabling such performance on CPUs paving the way for effective deployment of unsupervised monocular depth estimation even on embedded systems.

##### Abstract (translated by Google)
单个图像的无监督深度估计是一种非常有吸引力的技术，在机器人，自主导航，增强现实等方面具有多种含义。这个话题代表了一个非常具有挑战性的任务，深度学习的出现使得这个问题得到了很好的解决。但是，这些体系结构非常复杂。因此，实时性能只能利用耗电的GPU来实现，而这些GPU不允许推断以低功耗约束为特征的应用领域的深度图。为了解决这个问题，在本文中，我们提出了一种新颖的架构，能够使用从单个输入图像中提取的特征金字塔快速推断出CPU上甚至是嵌入式系统上的精确深度图。类似于最先进的技术，我们以无监督的方式训练我们的网络，将深度估计作为图像重建问题。 KITTI 2015数据集的广泛实验结果表明，与最佳性能方法相比，我们的网络具有相似的准确度，但复杂程度较低（约6％的参数），从而能够在1.7秒左右的树莓中推出KITTI图像的深度图Pi 3，在标准CPU上超过8 Hz。此外，通过交易效率的准确性，我们的网络允许分别以超过2 Hz和40 Hz的频率推断地图，仍然比大多数最先进的慢速方法更准确。据我们所知，这是第一种在CPU上实现这种性能的方法，即使在嵌入式系统上也能为有效部署无监督单眼深度估计铺平道路。

##### URL
[http://arxiv.org/abs/1806.11430](http://arxiv.org/abs/1806.11430)

##### PDF
[http://arxiv.org/pdf/1806.11430](http://arxiv.org/pdf/1806.11430)

