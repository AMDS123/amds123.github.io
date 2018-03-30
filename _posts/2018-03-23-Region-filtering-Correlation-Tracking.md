---
layout: post
title: "Region-filtering Correlation Tracking"
date: 2018-03-23 08:37:43
categories: arXiv_CV
tags: arXiv_CV Tracking Quantitative Relation
author: Nana Fan, Zhenyu He
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, correlation filters have demonstrated the excellent performance in visual tracking. However, the base training sample region is larger than the object region,including the Interference Region(IR). The IRs in training samples from cyclic shifts of the base training sample severely degrade the quality of a tracking model. In this paper, we propose the novel Region-filtering Correlation Tracking (RFCT) to address this problem. We immediately filter training samples by introducing a spatial map into the standard CF formulation. Compared with existing correlation filter trackers, our proposed tracker has the following advantages: (1) The correlation filter can be learned on a larger search region without the interference of the IR by a spatial map. (2) Due to processing training samples by a spatial map, it is more general way to control background information and target information in training samples. The values of the spatial map are not restricted, then a better spatial map can be explored. (3) The weight proportions of accurate filters are increased to alleviate model corruption. Experiments are performed on two benchmark datasets: OTB-2013 and OTB-2015. Quantitative evaluations on these benchmarks demonstrate that the proposed RFCT algorithm performs favorably against several state-of-the-art methods.

##### Abstract (translated by Google)
最近，相关滤波器已经证明了在视觉跟踪方面的出色表现。但是，基本训练样本区域大于目标区域，包括干涉区域（IR）。基训练样本的循环移位训练样本中的IR严重降低了跟踪模型的质量。在本文中，我们提出了新颖的区域滤波相关跟踪（RFCT）来解决这个问题。我们立即通过将空间图引入标准CF配方来过滤训练样本。与现有的相关滤波跟踪器相比，我们提出的跟踪器具有以下优点：（1）可以在较大的搜索区域上学习相关滤波器，而不受空间映射的干扰。 （2）由于采用空间图处理训练样本，在训练样本中控制背景信息和目标信息是较为普遍的方法。空间图的值不受限制，那么可以探索更好的空间图。 （3）增加精确过滤器的重量比例以减轻模型腐败。在两个基准数据集上进行实验：OTB-2013和OTB-2015。对这些基准的定量评估表明，所提出的RFCT算法对于几种最先进的方法有良好的表现。

##### URL
[https://arxiv.org/abs/1803.08687](https://arxiv.org/abs/1803.08687)

##### PDF
[https://arxiv.org/pdf/1803.08687](https://arxiv.org/pdf/1803.08687)

