---
layout: post
title: "Multi-camera Multi-Object Tracking"
date: 2017-09-20 20:08:16
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Optimization Relation
author: Wenqian Liu, Octavia Camps, Mario Sznaier
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a pipeline for multi-target visual tracking under multi-camera system. For multi-camera system tracking problem, efficient data association across cameras, and at the same time, across frames becomes more important than single-camera system tracking. However, most of the multi-camera tracking algorithms emphasis on single camera across frame data association. Thus in our work, we model our tracking problem as a global graph, and adopt Generalized Maximum Multi Clique optimization problem as our core algorithm to take both across frame and across camera data correlation into account all together. Furthermore, in order to compute good similarity scores as the input of our graph model, we extract both appearance and dynamic motion similarities. For appearance feature, Local Maximal Occurrence Representation(LOMO) feature extraction algorithm for ReID is conducted. When it comes to capturing the dynamic information, we build Hankel matrix for each tracklet of target and apply rank estimation with Iterative Hankel Total Least Squares(IHTLS) algorithm to it. We evaluate our tracker on the challenging Terrace Sequences from EPFL CVLAB as well as recently published Duke MTMC dataset.

##### Abstract (translated by Google)
在本文中，我们提出了一种多摄像机系统下的多目标视觉跟踪流水线。对于多摄像机系统跟踪问题，跨摄像机的高效数据关联，并且同时跨帧，变得比单摄像机系统跟踪更重要。然而，大多数多摄像机跟踪算法强调单个摄像机跨帧数据关联。因此，在我们的工作中，我们将跟踪问题建模为全局图，并采用通用最大多团优化问题作为核心算法，将跨帧和跨相机数据相关性考虑在一起。此外，为了计算好的相似度分数作为我们的图模型的输入，我们提取外观和动态运动的相似性。针对外观特征，进行了ReID的局部最大出现表示（LOMO）特征提取算法。在捕获动态信息时，我们针对每个目标的轨迹建立Hankel矩阵，并采用迭代Hankel最小二乘（IHTLS）算法对其进行秩估计。我们对来自EPFL CVLAB的具有挑战性的Terrace序列以及最近公布的Duke MTMC数据集进行评估。

##### URL
[https://arxiv.org/abs/1709.07065](https://arxiv.org/abs/1709.07065)

##### PDF
[https://arxiv.org/pdf/1709.07065](https://arxiv.org/pdf/1709.07065)

