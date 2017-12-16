---
layout: post
title: "Multiple Object Tracking with Kernelized Correlation Filters in Urban Mixed Traffic"
date: 2017-03-27 14:36:59
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Relation
author: Yuebin Yang, Guillaume-Alexandre Bilodeau
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the Kernelized Correlation Filters tracker (KCF) achieved competitive performance and robustness in visual object tracking. On the other hand, visual trackers are not typically used in multiple object tracking. In this paper, we investigate how a robust visual tracker like KCF can improve multiple object tracking. Since KCF is a fast tracker, many can be used in parallel and still result in fast tracking. We build a multiple object tracking system based on KCF and background subtraction. Background subtraction is applied to extract moving objects and get their scale and size in combination with KCF outputs, while KCF is used for data association and to handle fragmentation and occlusion problems. As a result, KCF and background subtraction help each other to take tracking decision at every frame. Sometimes KCF outputs are the most trustworthy (e.g. during occlusion), while in some other case, it is the background subtraction outputs. To validate the effectiveness of our system, the algorithm is demonstrated on four urban video recordings from a standard dataset. Results show that our method is competitive with state-of-the-art trackers even if we use a much simpler data association step.

##### Abstract (translated by Google)
最近，核化相关滤波器跟踪器（KCF）在视觉对象跟踪中获得了有竞争力的性能和鲁棒性。另一方面，视觉跟踪器通常不用于多个对象跟踪。在本文中，我们研究像KCF这样的强大的视觉跟踪器如何改进多个对象跟踪。由于KCF是一个快速跟踪器，因此可以并行使用许多跟踪器，并且仍然可以实现快速跟踪。我们构建了一个基于KCF和背景减法的多目标跟踪系统。背景减除被施加以提取移动的物体，并得到他们的规模和尺寸与KCF的输出组合，而KCF用于数据关联并处理碎片和遮挡的问题。结果，KCF和背景减法互相帮助在每一帧进行跟踪决定。有时KCF输出是最可信的（例如在遮挡期间），而在另一些情况下，它是背景减法输出。为了验证我们的系统的有效性，该算法在来自标准数据集的四个城市视频记录上进行了演示。结果表明，即使我们使用更简单的数据关联步骤，我们的方法仍然与最先进的跟踪器相竞争。

##### URL
[https://arxiv.org/abs/1611.02364](https://arxiv.org/abs/1611.02364)

##### PDF
[https://arxiv.org/pdf/1611.02364](https://arxiv.org/pdf/1611.02364)

