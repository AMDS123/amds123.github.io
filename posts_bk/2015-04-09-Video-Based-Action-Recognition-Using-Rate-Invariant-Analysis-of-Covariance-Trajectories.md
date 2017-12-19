---
layout: post
title: "Video-Based Action Recognition Using Rate-Invariant Analysis of Covariance Trajectories"
date: 2015-04-09 20:18:46
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Action_Recognition Video_Classification Classification Recognition
author: Zhengwu Zhang, Jingyong Su, Eric Klassen, Huiling Le, Anuj Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical classification of actions in videos is mostly performed by extracting relevant features, particularly covariance features, from image frames and studying time series associated with temporal evolutions of these features. A natural mathematical representation of activity videos is in form of parameterized trajectories on the covariance manifold, i.e. the set of symmetric, positive-definite matrices (SPDMs). The variable execution-rates of actions implies variable parameterizations of the resulting trajectories, and complicates their classification. Since action classes are invariant to execution rates, one requires rate-invariant metrics for comparing trajectories. A recent paper represented trajectories using their transported square-root vector fields (TSRVFs), defined by parallel translating scaled-velocity vectors of trajectories to a reference tangent space on the manifold. To avoid arbitrariness of selecting the reference and to reduce distortion introduced during this mapping, we develop a purely intrinsic approach where SPDM trajectories are represented by redefining their TSRVFs at the starting points of the trajectories, and analyzed as elements of a vector bundle on the manifold. Using a natural Riemannain metric on vector bundles of SPDMs, we compute geodesic paths and geodesic distances between trajectories in the quotient space of this vector bundle, with respect to the re-parameterization group. This makes the resulting comparison of trajectories invariant to their re-parameterization. We demonstrate this framework on two applications involving video classification: visual speech recognition or lip-reading and hand-gesture recognition. In both cases we achieve results either comparable to or better than the current literature.

##### Abstract (translated by Google)
视频中的动作的统计分类主要通过从图像帧中提取相关特征（特别是协方差特征）并研究与这些特征的时间演变关联的时间序列来执行。活动视频的自然数学表示形式为协方差流形上的参数化轨迹，即对称正定矩阵（SPDM）的集合。动作的可变执行速率意味着结果轨迹的可变参数化，并使其分类复杂化。由于行动类别对执行率不变，因此需要速率不变量度来比较轨迹。最近的一篇论文使用它们的传输的平方根向量场（TSRVF）表示轨迹，其通过将轨迹的缩放速度向量平行平移到歧管上的参考切向空间来定义。为了避免选择参考的任意性和减少在这个映射中引入的失真，我们开发了一种纯粹的内在方法，其中SPDM轨迹通过在轨迹的起点重新定义它们的TSRVF来表示，并且被分析为流形上的向量束的元素。在矢量束SPDM上使用自然Riemannain度量，我们计算相对于重新参数化组的矢量束的商空间中的轨迹之间的测地线路径和测地距离。这使得轨迹的结果比较不会重新参数化。我们在涉及视频分类的两个应用中展示了这个框架：视觉语音识别或唇读和手势识别。在这两种情况下，我们都达到了与当前文献相比甚至更好的结果。

##### URL
[https://arxiv.org/abs/1503.06699](https://arxiv.org/abs/1503.06699)

##### PDF
[https://arxiv.org/pdf/1503.06699](https://arxiv.org/pdf/1503.06699)

