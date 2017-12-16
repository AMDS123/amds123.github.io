---
layout: post
title: "RoomNet: End-to-End Room Layout Estimation"
date: 2017-08-07 19:58:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization
author: Chen-Yu Lee, Vijay Badrinarayanan, Tomasz Malisiewicz, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on the task of room layout estimation from a monocular RGB image. Prior works break the problem into two sub-tasks: semantic segmentation of floor, walls, ceiling to produce layout hypotheses, followed by an iterative optimization step to rank these hypotheses. In contrast, we adopt a more direct formulation of this problem as one of estimating an ordered set of room layout keypoints. The room layout and the corresponding segmentation is completely specified given the locations of these ordered keypoints. We predict the locations of the room layout keypoints using RoomNet, an end-to-end trainable encoder-decoder network. On the challenging benchmark datasets Hedau and LSUN, we achieve state-of-the-art performance along with 200x to 600x speedup compared to the most recent work. Additionally, we present optional extensions to the RoomNet architecture such as including recurrent computations and memory units to refine the keypoint locations under the same parametric capacity.

##### Abstract (translated by Google)
本文重点从单眼RGB图像的房间布局估计的任务。先前的工作将问题分解为两个子任务：地板，墙壁，天花板的语义分割以产生布局假设，然后是迭代优化步骤来排列这些假设。相反，我们采用这个问题的更直接的表达方式来估计一组有序的房间布局关键点。给定这些有序关键点的位置，完全指定房间布局和相应的分段。我们使用RoomNet（一种端到端的可训练编码器 - 解码器网络）来预测房间布局关键点的位置。在具有挑战性的基准数据集Hedau和LSUN上，与最新的工作相比，我们实现了最先进的性能以及200倍到600倍的加速。此外，我们提供了RoomNet架构的可选扩展，例如包括经常性计算和内存单元，以在相同参数容量下改进关键点位置。

##### URL
[https://arxiv.org/abs/1703.06241](https://arxiv.org/abs/1703.06241)

##### PDF
[https://arxiv.org/pdf/1703.06241](https://arxiv.org/pdf/1703.06241)

