---
layout: post
title: "FLIC: Fast Linear Iterative Clustering with Active Search"
date: 2017-11-21 03:29:42
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jia-Xin Zhao, Ren Bo, Qibin Hou, Ming-Ming Cheng, Paul Rosin
mathjax: true
---

* content
{:toc}

##### Abstract
Benefiting from its high efficiency and simplicity, Simple Linear Iterative Clustering (SLIC) remains one of the most popular over-segmentation tools. However, due to explicit enforcement of spatial similarity for region continuity, the boundary adaptation of SLIC is sub-optimal. It also has drawbacks on convergence rate as a result of both the fixed search region and separately doing the assignment step and the update step. In this paper, we propose an alternative approach to fix the inherent limitations of SLIC. In our approach, each pixel actively searches its corresponding segment under the help of its neighboring pixels, which naturally enables region coherence without being harmful to boundary adaptation. We also jointly perform the assignment and update steps, allowing high convergence rate. Extensive evaluations on Berkeley segmentation benchmark verify that our method outperforms competitive methods under various evaluation metrics. It also has the lowest time cost among existing methods (approximately 30fps for a 481x321 image on a single CPU core).

##### Abstract (translated by Google)
简单线性迭代聚类（SLIC）受益于其高效率和简单性，仍然是最流行的过分割工具之一。然而，由于区域连续性的空间相似性的明确实施，SLIC的边界适应是次优的。由于固定搜索区域和分别执行分配步骤和更新步骤，收敛速度也有缺陷。在本文中，我们提出了一种解决SLIC固有限制的替代方法。在我们的方法中，每个像素在其相邻像素的帮助下主动搜索其相应的片段，这自然使得区域相干性不会对边界适应性造成伤害。我们还共同执行分配和更新步骤，允许高收敛速度。伯克利分割基准的广泛评估证实，我们的方法在各种评估指标下胜过竞争方法。它在现有方法中的时间成本也最低（单个CPU内核上的481x321图像大约为30fps）。

##### URL
[https://arxiv.org/abs/1612.01810](https://arxiv.org/abs/1612.01810)

##### PDF
[https://arxiv.org/pdf/1612.01810](https://arxiv.org/pdf/1612.01810)

