---
layout: post
title: "In Defense of Single-column Networks for Crowd Counting"
date: 2018-08-18 21:08:57
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ze Wang, Zehao Xiao, Kai Xie, Qiang Qiu, Xiantong Zhen, Xianbin Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting usually addressed by density estimation becomes an increasingly important topic in computer vision due to its widespread applications in video surveillance, urban planning, and intelligence gathering. However, it is essentially a challenging task because of the greatly varied sizes of objects, coupled with severe occlusions and vague appearance of extremely small individuals. Existing methods heavily rely on multi-column learning architectures to extract multi-scale features, which however suffer from heavy computational cost, especially undesired for crowd counting. In this paper, we propose the single-column counting network (SCNet) for efficient crowd counting without relying on multi-column networks. SCNet consists of residual fusion modules (RFMs) for multi-scale feature extraction, a pyramid pooling module (PPM) for information fusion, and a sub-pixel convolutional module (SPCM) followed by a bilinear upsampling layer for resolution recovery. Those proposed modules enable our SCNet to fully capture multi-scale features in a compact single-column architecture and estimate high-resolution density map in an efficient way. In addition, we provide a principled paradigm for density map generation and data augmentation for training, which shows further improved performance. Extensive experiments on three benchmark datasets show that our SCNet delivers new state-of-the-art performance and surpasses previous methods by large margins, which demonstrates the great effectiveness of SCNet as a single-column network for crowd counting.

##### Abstract (translated by Google)
由于其在视频监控，城市规划和情报收集中的广泛应用，通常通过密度估计解决的人群计数成为计算机视觉中越来越重要的主题。然而，它本质上是一项具有挑战性的任务，因为物体的大小变化很大，加上严重的遮挡和极小的个体的模糊外观。现有方法严重依赖于多列学习架构来提取多尺度特征，然而其具有大量计算成本，特别是对于人群计数而言是不期望的。在本文中，我们提出了单列计数网络（SCNet），用于有效的人群计数，而不依赖于多列网络。 SCNet包括用于多尺度特征提取的残余聚变模块（RFM），用于信息融合的金字塔聚合模块（PPM），以及用于分辨率恢复的双线性上采样层的子像素卷积模块（SPCM）。这些建议的模块使我们的SCNet能够在紧凑的单列架构中完全捕获多尺度特征，并以有效的方式估算高分辨率密度图。此外，我们为密度图生成和培训数据增强提供了一个原则范例，显示了进一步改进的性能。对三个基准数据集的大量实验表明，我们的SCNet提供了新的最先进的性能，并且通过大的利润超过了以前的方法，这证明了SCNet作为人群计数的单列网络的巨大效力。

##### URL
[http://arxiv.org/abs/1808.06133](http://arxiv.org/abs/1808.06133)

##### PDF
[http://arxiv.org/pdf/1808.06133](http://arxiv.org/pdf/1808.06133)

