---
layout: post
title: "On the Relations of Correlation Filter Based Trackers and Struck"
date: 2017-11-25 14:44:29
categories: arXiv_CV
tags: arXiv_CV Regularization Relation
author: Jinqiao Wang, Ming Tang, Linyu Zheng, Jiayi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, two types of trackers, namely correlation filter based tracker (CF tracker) and structured output tracker (Struck), have exhibited the state-of-the-art performance. However, there seems to be lack of analytic work on their relations in the computer vision community. In this paper, we investigate two state-of-the-art CF trackers, i.e., spatial regularization discriminative correlation filter (SRDCF) and correlation filter with limited boundaries (CFLB), and Struck, and reveal their relations. Specifically, after extending the CFLB to its multiple channel version we prove the relation between SRDCF and CFLB on the condition that the spatial regularization factor of SRDCF is replaced by the masking matrix of CFLB. We also prove the asymptotical approximate relation between SRDCF and Struck on the conditions that the spatial regularization factor of SRDCF is replaced by an indicator function of object bounding box, the weights of SRDCF in its loss item are replaced by those of Struck, the linear kernel is employed by Struck, and the search region tends to infinity. Extensive experiments on public benchmarks OTB50 and OTB100 are conducted to verify our theoretical results. Moreover, we explain how detailed differences among SRDCF, CFLB, and Struck would give rise to slightly different performances on visual sequences

##### Abstract (translated by Google)
近年来，基于相关滤波器的跟踪器（CF跟踪器）和结构化输出跟踪器（Struck）两种跟踪器展现了最先进的性能。但是，计算机视觉领域的关系似乎缺乏分析性的工作。在本文中，我们研究了两种最先进的CF跟踪器，即空间正则化鉴别相关滤波器（SRDCF）和有限边界相关滤波器（CFLB）以及Struck，并揭示它们之间的关系。具体而言，在将CFLB扩展为多通道版本后，在SRDCF的空间正则化因子被CFLB的掩蔽矩阵所替代的情况下，证明了SRDCF与CFLB之间的关系。在SRDCF的空间正则化因子被对象边界框的指示函数替代的条件下，证明了SRDCF与Struck之间的渐近近似关系，损失项中的SRDCF的权重被Struck中的线性核被Struck聘用，搜索区域趋于无限。在公共基准OTB50和OTB100上进行了大量的实验来验证我们的理论结果。此外，我们解释了SRDCF，CFLB和Struck之间的详细差异如何在视觉序列上产生略微不同的表现

##### URL
[https://arxiv.org/abs/1711.09243](https://arxiv.org/abs/1711.09243)

##### PDF
[https://arxiv.org/pdf/1711.09243](https://arxiv.org/pdf/1711.09243)

