---
layout: post
title: "Learning Aggregated Transmission Propagation Networks for Haze Removal and Beyond"
date: 2017-11-18 01:37:04
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Enhancement Optimization
author: Risheng Liu, Xin Fan, Minjun Hou, Zhiying Jiang, Zhongxuan Luo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Single image dehazing is an important low-level vision task with many applications. Early researches have investigated different kinds of visual priors to address this problem. However, they may fail when their assumptions are not valid on specific images. Recent deep networks also achieve relatively good performance in this task. But unfortunately, due to the disappreciation of rich physical rules in hazes, large amounts of data are required for their training. More importantly, they may still fail when there exist completely different haze distributions in testing images. By considering the collaborations of these two perspectives, this paper designs a novel residual architecture to aggregate both prior (i.e., domain knowledge) and data (i.e., haze distribution) information to propagate transmissions for scene radiance estimation. We further present a variational energy based perspective to investigate the intrinsic propagation behavior of our aggregated deep model. In this way, we actually bridge the gap between prior driven models and data driven networks and leverage advantages but avoid limitations of previous dehazing approaches. A lightweight learning framework is proposed to train our propagation network. Finally, by introducing a taskaware image decomposition formulation with flexible optimization scheme, we extend the proposed model for more challenging vision tasks, such as underwater image enhancement and single image rain removal. Experiments on both synthetic and realworld images demonstrate the effectiveness and efficiency of the proposed framework.

##### Abstract (translated by Google)
单图像除雾是一个重要的低层次视觉任务，有很多应用。早期的研究已经研究了不同类型的视觉先验来解决这个问题。但是，当他们的假设对特定图像无效时，他们可能会失败。最近的深度网络在这个任务中也取得了比较好的表现。但不幸的是，由于雾霾中丰富的物理规则的失败，他们的培训需要大量的数据。更重要的是，当测试图像中存在完全不同的雾度分布时，它们可能仍然会失败。通过考虑这两个观点的协作，本文设计了一种新颖的残差体系结构来聚合先验（即，领域知识）和数据（即，雾度分布）信息以传播用于场景辐射度估计的传输。我们进一步提出了一个基于变分能量的观点来调查我们的聚合深层模型的固有传播行为。通过这种方式，我们实际上弥合了先前的驱动模型和数据驱动的网络之间的差距，并且利用了优势，但是避免了先前除雾方法的限制。提出了一个轻量级的学习框架来训练我们的传播网络。最后，通过引入具有灵活优化方案的taskaware图像分解公式，将所提出的模型扩展到更具挑战性的视觉任务，如水下图像增强和单幅图像降雨。在合成和现实世界的图像实验证明了所提出的框架的有效性和效率。

##### URL
[https://arxiv.org/abs/1711.06787](https://arxiv.org/abs/1711.06787)

##### PDF
[https://arxiv.org/pdf/1711.06787](https://arxiv.org/pdf/1711.06787)

