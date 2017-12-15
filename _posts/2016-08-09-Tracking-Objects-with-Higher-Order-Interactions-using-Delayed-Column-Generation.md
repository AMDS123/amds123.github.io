---
layout: post
title: "Tracking Objects with Higher Order Interactions using Delayed Column Generation"
date: 2016-08-09 05:44:51
categories: arXiv_CV
tags: arXiv_CV Tracking Inference Detection
author: Shaofei Wang, Steffen Wolf, Charless Fowlkes, Julian Yarkony
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of multi-target tracking and data association in video. We formulate this in terms of selecting a subset of high-quality tracks subject to the constraint that no pair of selected tracks is associated with a common detection (of an object). This objective is equivalent to the classic NP-hard problem of finding a maximum-weight set packing (MWSP) where tracks correspond to sets and is made further difficult since the number of candidate tracks grows exponentially in the number of detections. We present a relaxation of this combinatorial problem that uses a column generation formulation where the pricing problem is solved via dynamic programming to efficiently explore the space of tracks. We employ row generation to tighten the bound in such a way as to preserve efficient inference in the pricing problem. We show the practical utility of this algorithm for tracking problems in natural and biological video datasets.

##### Abstract (translated by Google)
我们研究视频中的多目标跟踪和数据关联问题。我们用选择高质量音轨的一个子集的方式来制定这个条件，但这个限制条件是没有一对选定的音轨与（对象的）一个共同的检测相关联。这个目标相当于寻找最大重量集合包装（MWSP）的经典NP难问题，其中轨道对应于集合，并且由于候选轨道的数目在检测数量中指数增长而变得更加困难。我们目前放松这个组合问题，使用列生成公式，定价问题是通过动态规划解决，以有效地探索轨道的空间。我们采用排产生的方式来收紧边界，从而在定价问题中保持有效的推断。我们展示了这个算法在自然和生物视频数据集中跟踪问题的实际效用。

##### URL
[https://arxiv.org/abs/1512.02413](https://arxiv.org/abs/1512.02413)

##### PDF
[https://arxiv.org/pdf/1512.02413](https://arxiv.org/pdf/1512.02413)

