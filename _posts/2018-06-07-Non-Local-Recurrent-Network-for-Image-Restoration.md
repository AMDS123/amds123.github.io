---
layout: post
title: "Non-Local Recurrent Network for Image Restoration"
date: 2018-06-07 22:50:49
categories: arXiv_CV
tags: arXiv_CV Super_Resolution RNN Relation
author: Ding Liu, Bihan Wen, Yuchen Fan, Chen Change Loy, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Many classic methods have shown non-local self-similarity in natural images to be an effective prior for image restoration. However, it remains unclear and challenging to make use of this intrinsic property via deep networks. In this paper, we propose a non-local recurrent network (NLRN) as the first attempt to incorporate non-local operations into a recurrent neural network (RNN) for image restoration. The main contributions of this work are: (1) Unlike existing methods that measure self-similarity in an isolated manner, the proposed non-local module can be flexibly integrated into existing deep networks for end-to-end training to capture deep feature correlation between each location and its neighborhood. (2) We fully employ the RNN structure for its parameter efficiency and allow deep feature correlation to be propagated along adjacent recurrent states. This new design boosts robustness against inaccurate correlation estimation due to severely degraded images. (3) We show that it is essential to maintain a confined neighborhood for computing deep feature correlation given degraded images. This is in contrast to existing practice that deploys the whole image. Extensive experiments on both image denoising and super-resolution tasks are conducted. Thanks to the recurrent non-local operations and correlation propagation, the proposed NLRN achieves superior results to state-of-the-art methods with much fewer parameters.

##### Abstract (translated by Google)
许多经典的方法都表明自然图像中的非局部自相似性是图像恢复的有效先验。但是，通过深度网络来利用这种内在特性仍然不清楚和具有挑战性。在本文中，我们提出一种非局部循环网络（NLRN）作为第一次将非本地操作并入用于图像恢复的递归神经网络（RNN）的尝试。这项工作的主要贡献是：（1）与现有的以独立方式测量自相似性的方法不同，所提出的非本地模块可以灵活地集成到现有的深度网络中进行端到端训练，以捕获深度特征相关性在每个位置和它的邻居之间。 （2）我们充分利用了RNN结构的参数效率，并且允许深度特征相关性沿着相邻的递归状态传播。这种新设计提高了鲁棒性，防止由于严重退化的图像造成的不准确的相关性估计。 （3）我们表明，对于给定退化图像计算深度特征相关性，维持一个受限邻域是至关重要的。这与部署整个图像的现有实践形成对比。对图像去噪和超分辨率任务进行了大量实验。由于经常性的非本地操作和相关性传播，所提出的NLRN能够以最少的参数获得优异的结果。

##### URL
[http://arxiv.org/abs/1806.02919](http://arxiv.org/abs/1806.02919)

##### PDF
[http://arxiv.org/pdf/1806.02919](http://arxiv.org/pdf/1806.02919)

