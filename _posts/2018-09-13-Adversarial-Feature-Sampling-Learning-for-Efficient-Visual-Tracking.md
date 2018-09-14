---
layout: post
title: "Adversarial Feature Sampling Learning for Efficient Visual Tracking"
date: 2018-09-13 02:06:18
categories: arXiv_CV
tags: arXiv_CV Adversarial Tracking CNN Detection
author: Yingjie Yin, Lei Zhang, De Xu, Xingang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The tracking-by-detection framework usually consist of two stages: drawing samples around the target object in the first stage and classifying each sample as the target object or background in the second stage. Current popular trackers based on tracking-by-detection framework typically draw samples in the raw image as the inputs of deep convolution networks in the first stage, which usually results in high computational burden and low running speed. In this paper, we propose a new visual tracking method using sampling deep convolutional features to address this problem. Only one cropped image around the target object is input into the designed deep convolution network and the samples is sampled on the feature maps of the network by spatial bilinear resampling. In addition, a generative adversarial network is integrated into our network framework to augment positive samples and improve the tracking performance. Extensive experiments on benchmark datasets demonstrate that the proposed method achieves a comparable performance to state-of-the-art trackers and accelerates tracking-by-detection trackers based on raw-image samples effectively.

##### Abstract (translated by Google)
逐个检测框架通常包括两个阶段：在第一阶段中围绕目标对象绘制样本，并将每个样本分类为第二阶段中的目标对象或背景。当前基于逐个检测框架的流行跟踪器通常在原始图像中绘制样本作为第一阶段中的深度卷积网络的输入，这通常导致高计算负担和低运行速度。在本文中，我们提出了一种新的视觉跟踪方法，使用采样深度卷积特征来解决这个问题。仅将目标对象周围的一个裁剪图像输入到设计的深度卷积网络中，并且通过空间双线性重采样在网络的特征图上对样本进行采样。此外，我们的网络框架中集成了生成对抗网络，以增强正样本并提高跟踪性能。对基准数据集的大量实验表明，所提出的方法实现了与最先进的跟踪器相当的性能，并有效地加速了基于原始图像样本的跟踪检测跟踪器。

##### URL
[http://arxiv.org/abs/1809.04741](http://arxiv.org/abs/1809.04741)

##### PDF
[http://arxiv.org/pdf/1809.04741](http://arxiv.org/pdf/1809.04741)

