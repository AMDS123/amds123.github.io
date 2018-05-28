---
layout: post
title: "Greedy Graph Searching for Vascular Tracking in Angiographic Image Sequences"
date: 2018-05-25 00:53:57
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Huihui Fang, Jian Yang, Jianjun Zhu, Danni Ai, Yong Huang, Yurong Jiang, Hong Song, Yongtian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Vascular tracking of angiographic image sequences is one of the most clinically important tasks in the diagnostic assessment and interventional guidance of cardiac disease. However, this task can be challenging to accomplish because of unsatisfactory angiography image quality and complex vascular structures. Thus, this study proposed a new greedy graph search-based method for vascular tracking. Each vascular branch is separated from the vasculature and is tracked independently. Then, all branches are combined using topology optimization, thereby resulting in complete vasculature tracking. A gray-based image registration method was applied to determine the tracking range, and the deformation field between two consecutive frames was calculated. The vascular branch was described using a vascular centerline extraction method with multi-probability fusion-based topology optimization. We introduce an undirected acyclic graph establishment technique. A greedy search method was proposed to acquire all possible paths in the graph that might match the tracked vascular branch. The final tracking result was selected by branch matching using dynamic time warping with a DAISY descriptor. The solution to the problem reflected both the spatial and textural information between successive frames. Experimental results demonstrated that the proposed method was effective and robust for vascular tracking, attaining a F1 score of 0.89 on a single branch dataset and 0.88 on a vessel tree dataset. This approach provided a universal solution to address the problem of filamentary structure tracking.

##### Abstract (translated by Google)
血管造影图像序列的跟踪是心脏疾病诊断评估和介入指导中最重要的临床任务之一。然而，由于血管造影图像质量不理想和血管结构复杂，这项任务可能难以完成。因此，本研究提出了一种新的基于贪心图搜索的血管追踪方法。每个血管分支从血管分离并且被独立地跟踪。然后，所有分支都使用拓扑优化进行组合，从而导致完整的脉管系统跟踪。采用基于灰度的图像配准方法确定跟踪范围，计算两个连续帧之间的变形场。使用血管中心线提取方法和多概率融合拓扑优化描述血管分支。我们介绍一种无向非循环图建立技术。提出了一种贪心搜索方法来获取图表中可能匹配被跟踪血管分支的所有可能路径。最终的跟踪结果是通过使用DAISY描述符进行动态时间规整的分支匹配来选择的。问题的解决方案反映了连续帧之间的空间和纹理信息。实验结果表明，所提出的方法对血管跟踪有效且鲁棒，在单个分支数据集上获得0.89的F1分数，在血管树数据集上获得0.88。这种方法提供了解决丝状结构跟踪问题的通用解决方案。

##### URL
[http://arxiv.org/abs/1805.09940](http://arxiv.org/abs/1805.09940)

##### PDF
[http://arxiv.org/pdf/1805.09940](http://arxiv.org/pdf/1805.09940)

