---
layout: post
title: "Cluster-Wise Ratio Tests for Fast Camera Localization"
date: 2017-05-20 18:02:46
categories: arXiv_CV
tags: arXiv_CV
author: Raúl Díaz, Charless C. Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
Feature point matching for camera localization suffers from scalability problems. Even when feature descriptors associated with 3D scene points are locally unique, as coverage grows, similar or repeated features become increasingly common. As a result, the standard distance ratio-test used to identify reliable image feature points is overly restrictive and rejects many good candidate matches. We propose a simple coarse-to-fine strategy that uses conservative approximations to robust local ratio-tests that can be computed efficiently using global approximate k-nearest neighbor search. We treat these forward matches as votes in camera pose space and use them to prioritize back-matching within candidate camera pose clusters, exploiting feature co-visibility captured by clustering the 3D model camera pose graph. This approach achieves state-of-the-art camera localization results on a variety of popular benchmarks, outperforming several methods that use more complicated data structures and that make more restrictive assumptions on camera pose. We also carry out diagnostic analyses on a difficult test dataset containing globally repetitive structure that suggest our approach successfully adapts to the challenges of large-scale image localization.

##### Abstract (translated by Google)
相机本地化的特征点匹配遭受可伸缩性问题。即使与三维场景点相关联的特征描述符在本地是唯一的，随着覆盖率的增加，类似或重复的特征也变得越来越普遍。结果，用于识别可靠图像特征点的标准距离比率检验过于严格，并且拒绝许多好的候选匹配。我们提出了一个简单的从粗到精的策略，使用保守的近似来鲁棒的局部比率测试，可以使用全局近似k-最近邻搜索有效地计算。我们将这些前向匹配视为摄像机姿态空间中的投票，并使用它们来优先考虑候选摄像机姿态集群内的后向匹配，利用通过对3D模型摄像机姿态图进行聚类而捕获的特征共同可见性。这种方法在各种流行的基准测试中实现了最先进的相机定位结果，优于使用更复杂数据结构的几种方法，并且在相机姿态上做出更多限制性的假设。我们还对包含全球重复结构的困难测试数据集进行诊断分析，这表明我们的方法成功地适应了大规模图像定位的挑战。

##### URL
[https://arxiv.org/abs/1612.01689](https://arxiv.org/abs/1612.01689)

##### PDF
[https://arxiv.org/pdf/1612.01689](https://arxiv.org/pdf/1612.01689)

