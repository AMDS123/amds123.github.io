---
layout: post
title: "LiteFlowNet: A Lightweight Convolutional Neural Network for Optical Flow Estimation"
date: 2018-05-18 03:29:54
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference
author: Tak-Wai Hui, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
FlowNet2, the state-of-the-art convolutional neural network (CNN) for optical flow estimation, requires over 160M parameters to achieve accurate flow estimation. In this paper we present an alternative network that outperforms FlowNet2 on the challenging Sintel final pass and KITTI benchmarks, while being 30 times smaller in the model size and 1.36 times faster in the running speed. This is made possible by drilling down to architectural details that might have been missed in the current frameworks: (1) We present a more effective flow inference approach at each pyramid level through a lightweight cascaded network. It not only improves flow estimation accuracy through early correction, but also permits seamless incorporation of descriptor matching in our network. (2) We present a novel flow regularization layer to ameliorate the issue of outliers and vague flow boundaries by using a feature-driven local convolution. (3) Our network owns an effective structure for pyramidal feature extraction and embraces feature warping rather than image warping as practiced in FlowNet2. Our code and trained models are available at https://github.com/twhui/LiteFlowNet.

##### Abstract (translated by Google)
用于光流估计的最先进的卷积神经网络（CNN）FlowNet2需要超过160M的参数才能实现精确的流量估计。在本文中，我们提出了一个替代网络，其在具有挑战性的Sintel最终通过和KITTI基准测试中胜过FlowNet2，同时在模型尺寸上小30倍，在运行速度上快1.36倍。这可以通过深入到当前框架中可能错过的架构细节来实现：（1）我们通过轻量级联网络在每个金字塔等级提供更有效的流量推断方法。它不仅通过早期修正提高了流量估计的准确性，而且还允许在我们的网络中无缝并入描述符匹配。 （2）通过使用特征驱动的局部卷积，我们提出了一种新颖的流动正则化层来改善异常值和模糊流动边界的问题。 （3）我们的网络拥有用于金字塔特征提取的有效结构，并且包含了FlowNet2中实现的特征翘曲而非图像翘曲。我们的代码和训练有素的模型可在https://github.com/twhui/LiteFlowNet上找到。

##### URL
[http://arxiv.org/abs/1805.07036](http://arxiv.org/abs/1805.07036)

##### PDF
[http://arxiv.org/pdf/1805.07036](http://arxiv.org/pdf/1805.07036)

