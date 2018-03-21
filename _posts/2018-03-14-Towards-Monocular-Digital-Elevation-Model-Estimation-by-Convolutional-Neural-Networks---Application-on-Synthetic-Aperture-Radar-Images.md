---
layout: post
title: "Towards Monocular Digital Elevation Model Estimation by Convolutional Neural Networks - Application on Synthetic Aperture Radar Images"
date: 2018-03-14 16:32:18
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Gabriele Costante, Thomas A. Ciarfuglia, Filippo Biondi
mathjax: true
---

* content
{:toc}

##### Abstract
Synthetic aperture radar (SAR) interferometry (InSAR) is performed using repeat-pass geometry. InSAR technique is used to estimate the topographic reconstruction of the earth surface. The main problem of the range-Doppler focusing technique is the nature of the two-dimensional SAR result, affected by the layover indetermination. In order to resolve this problem, a minimum of two sensor acquisitions, separated by a baseline and extended in the cross-slant-range, are needed. However, given its multi-temporal nature, these techniques are vulnerable to atmosphere and Earth environment parameters variation in addition to physical platform instabilities. Furthermore, either two radars are needed or an interferometric cycle is required (that spans from days to weeks), which makes real time DEM estimation impossible. In this work, the authors propose a novel experimental alternative to the InSAR method that uses single-pass acquisitions, using a data driven approach implemented by Deep Neural Networks. We propose a fully Convolutional Neural Network (CNN) Encoder-Decoder architecture, training it on radar images in order to estimate DEMs from single pass image acquisitions. Our results on a set of Sentinel images show that this method is able to learn to some extent the statistical properties of the DEM. The results of this exploratory analysis are encouraging and open the way to the solution of single-pass DEM estimation problem with data driven approaches.

##### Abstract (translated by Google)
合成孔径雷达（SAR）干涉测量（InSAR）使用重复通过几何进行。 InSAR技术用于估计地球表面的地形重建。距离多普勒聚焦技术的主要问题是二维SAR结果的性质，受到不确定性的影响。为了解决这个问题，需要至少两个传感器采集，由基线分开并在交叉倾斜范围内扩展。然而，鉴于其多时间特性，这些技术除了物理平台不稳定性外，还易受大气和地球环境参数变化的影响。此外，无论是需要两个雷达还是需要一个干涉测量周期（从几天到几周），这使得实时DEM估计变得不可能。在这项工作中，作者提出了一种新的InSAR方法的实验替代方法，该方法使用单通采集，采用深度神经网络实现的数据驱动方法。我们提出一个完全的卷积神经网络（CNN）编码器 - 解码器架构，在雷达图像上进行训练，以便通过单次图像采集来估计DEM。我们在一组Sentinel图像上的结果表明，这种方法能够在一定程度上学习DEM的统计特性。这种探索性分析的结果是令人鼓舞的，并为以数据驱动方法解决单程DEM估计问题开辟了道路。

##### URL
[https://arxiv.org/abs/1803.05387](https://arxiv.org/abs/1803.05387)

##### PDF
[https://arxiv.org/pdf/1803.05387](https://arxiv.org/pdf/1803.05387)

