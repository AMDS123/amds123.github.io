---
layout: post
title: "Single Image Dehazing Based on Generic Regularity"
date: 2018-08-26 18:47:08
categories: arXiv_CV
tags: arXiv_CV Regularization Deep_Learning
author: Kushal Borkar, Snehasis Mukherjee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel technique for single image dehazing. Most of the state-of-the-art methods for single image dehazing relies either on Dark Channel Prior (DCP) or on Color line. The proposed method combines the two different approaches. We initially compute the dark channel prior and then apply a Nearest-Neighbor (NN) based regularization technique to obtain a smooth transmission map of the hazy image. We consider the effect of airlight on the image by using the color line model to assess the commitment of airlight in each patch of the image and interpolate at the local neighborhood where the estimate is unreliable. The NN based regularization of the DCP can remove the haze, whereas, the color line based interpolation of airlight effect makes the proposed system robust against the variation of haze within an image due to multiple light sources. The proposed method is tested on benchmark datasets and shows promising results compared to the state-of-the-art, including the deep learning based methods, which require a huge computational setup. Moreover, the proposed method outperforms the recent deep learning based methods when applied on images with sky regions.

##### Abstract (translated by Google)
本文提出了一种新的单图像去雾技术。用于单个图像去雾的大多数最先进的方法依赖于暗通道先前（DCP）或彩色线。所提出的方法结合了两种不同的方法。我们最初先计算暗通道，然后应用基于最近邻（NN）的正则化技术来获得模糊图像的平滑透射图。我们通过使用色线模型来评估空气对图像的影响，以评估图像的每个片段中的空气的承诺，并在估计不可靠的局部邻域处进行插值。基于NN的DCP正则化可以消除雾度，而基于颜色线的空气效应内插使得所提出的系统对由于多个光源引起的图像内的雾度变化具有鲁棒性。所提出的方法在基准数据集上进行测试，并且与现有技术相比显示出有希望的结果，包括需要大量计算设置的基于深度学习的方法。此外，当应用于具有天空区域的图像时，所提出的方法优于最近的基于深度学习的方法。

##### URL
[http://arxiv.org/abs/1808.08610](http://arxiv.org/abs/1808.08610)

##### PDF
[http://arxiv.org/pdf/1808.08610](http://arxiv.org/pdf/1808.08610)

