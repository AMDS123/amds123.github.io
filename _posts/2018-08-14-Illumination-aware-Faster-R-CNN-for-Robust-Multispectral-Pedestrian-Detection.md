---
layout: post
title: "Illumination-aware Faster R-CNN for Robust Multispectral Pedestrian Detection"
date: 2018-08-14 17:34:09
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Chengyang Li, Dan Song, Ruofeng Tong, Min Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Multispectral images of color-thermal pairs have shown more effective than a single color channel for pedestrian detection, especially under challenging illumination conditions. However, there is still a lack of studies on how to fuse the two modalities effectively. In this paper, we deeply compare six different convolutional network fusion architectures and analyse their adaptations, enabling a vanilla architecture to obtain detection performances comparable to the state-of-the-art results. Further, we discover that pedestrian detection confidences from color or thermal images are correlated with illumination conditions. With this in mind, we propose an Illumination-aware Faster R-CNN (IAF RCNN). Specifically, an Illumination-aware Network is introduced to give an illumination measure of the input image. Then we adaptively merge color and thermal sub-networks via a gate function defined over the illumination value. The experimental results on KAIST Multispectral Pedestrian Benchmark validate the effectiveness of the proposed IAF R-CNN.

##### Abstract (translated by Google)
彩色 - 热对的多光谱图像显示出比单个颜色通道更有效的行人检测，特别是在具有挑战性的照明条件下。然而，仍然缺乏有关如何有效融合这两种方式的研究。在本文中，我们深入比较了六种不同的卷积网络融合架构并分析了它们的适应性，使得vanilla架构能够获得与最先进结果相当的检测性能。此外，我们发现来自颜色或热图像的行人检测置信度与照明条件相关。考虑到这一点，我们提出了一种照明感知更快的R-CNN（IAF RCNN）。具体地，引入照明感知网络以给出输入图像的照明度量。然后，我们通过在照明值上定义的门函数自适应地合并颜色和热子网络。 KAIST多光谱行人基准的实验结果验证了所提出的IAF R-CNN的有效性。

##### URL
[http://arxiv.org/abs/1803.05347](http://arxiv.org/abs/1803.05347)

##### PDF
[http://arxiv.org/pdf/1803.05347](http://arxiv.org/pdf/1803.05347)

