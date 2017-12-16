---
layout: post
title: "Effective Image Retrieval via Multilinear Multi-index Fusion"
date: 2017-09-27 01:59:17
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Sparse Optimization
author: Zhizhong Zhang, Yuan Xie, Wensheng Zhang, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-index fusion has demonstrated impressive performances in retrieval task by integrating different visual representations in a unified framework. However, previous works mainly consider propagating similarities via neighbor structure, ignoring the high order information among different visual representations. In this paper, we propose a new multi-index fusion scheme for image retrieval. By formulating this procedure as a multilinear based optimization problem, the complementary information hidden in different indexes can be explored more thoroughly. Specially, we first build our multiple indexes from various visual representations. Then a so-called index-specific functional matrix, which aims to propagate similarities, is introduced for updating the original index. The functional matrices are then optimized in a unified tensor space to achieve a refinement, such that the relevant images can be pushed more closer. The optimization problem can be efficiently solved by the augmented Lagrangian method with theoretical convergence guarantee. Unlike the traditional multi-index fusion scheme, our approach embeds the multi-index subspace structure into the new indexes with sparse constraint, thus it has little additional memory consumption in online query stage. Experimental evaluation on three benchmark datasets reveals that the proposed approach achieves the state-of-the-art performance, i.e., N-score 3.94 on UKBench, mAP 94.1\% on Holiday and 62.39\% on Market-1501.

##### Abstract (translated by Google)
多索引融合在检索任务中表现出了令人印象深刻的表现，将不同的视觉表现集成在一个统一的框架中但以往的工作主要考虑通过邻居结构来传播相似性，忽略不同视觉表示之间的高阶信息。在本文中，我们提出了一种新的多索引图像检索融合方案。通过将这一过程制定为一个多线性优化问题，可以更深入地探索隐藏在不同指标中的互补信息。特别是，我们首先从各种视觉表示构建我们的多个索引。然后引入一个旨在传播相似性的索引专用函数矩阵来更新原始索引。然后在统一的张量空间中对函数矩阵进行优化以实现细化，使得相关图像可以更加靠近。用理论收敛保证的增广拉格朗日方法可以有效解决优化问题。与传统的多指标融合方案不同，我们的方法将多指标子空间结构嵌入到具有稀疏约束的新指标中，因此在线查询阶段的附加消耗少。对三个基准数据集进行的实验评估显示，所提出的方法达到了最先进的性能，即UKBench上的N分数为3.94，假日上的MAP为94.1％，市场上的1501为62.39％。

##### URL
[https://arxiv.org/abs/1709.09304](https://arxiv.org/abs/1709.09304)

##### PDF
[https://arxiv.org/pdf/1709.09304](https://arxiv.org/pdf/1709.09304)

