---
layout: post
title: "Fine-grained Pattern Matching Over Streaming Time Series"
date: 2017-12-01 23:45:48
categories: arXiv_CV
tags: arXiv_CV
author: Rong Kang, Chen Wang, Peng Wang, Yuting Ding, Jianmin Wang
---

* content
{:toc}

##### Abstract
Pattern matching of streaming time series with lower latency under limited computing resource comes to a critical problem, especially as the growth of Industry 4.0 and Industry Internet of Things. However, against traditional single pattern matching problem, a pattern may contain multiple segments representing different statistical properties or physical meanings for more precise and expressive matching in real world. Hence, we formulate a new problem, called "fine-grained pattern matching", which allows users to specify varied granularities of matching deviation to different segments of a given pattern, and fuzzy regions for adaptive breakpoints determination between consecutive segments. In this paper, we propose a novel two-phase approach. In the pruning phase, we introduce Equal-Length Block (ELB) representation together with Block-Skipping Pruning (BSP) policy, which guarantees low cost feature calculation, effective pruning and no false dismissals. In the post-processing phase, a delta-function is proposed to enable us to conduct exact matching in linear complexity. Extensive experiments are conducted to evaluate on synthetic and real-world datasets, which illustrates that our algorithm outperforms the brute-force method and MSM, a multi-step filter mechanism over the multi-scaled representation.

##### Abstract (translated by Google)
在有限的计算资源下，流延时间序列与延迟较低的模式匹配成为一个关键问题，尤其是随着工业4.0和工业物联网的发展。然而，与传统的单一模式匹配问题相比，一个模式可能包含多个代表不同统计特性或物理意义的片段，以便在现实世界中进行更精确和更具表现力的匹配。因此，我们制定了一个新的问题，称为“细粒度模式匹配”，它允许用户指定不同粒度的匹配偏差给定模式的不同部分，模糊区域用于连续线段之间的自适应断点确定。在本文中，我们提出了一种新颖的两阶段方法。在修剪阶段，我们引入了等长块（ELB）表示和块跳过修剪（BSP）策略，保证了低成本特征计算，有效的修剪和没有错误的解雇。在后处理阶段，提出了一个delta函数，使我们能够进行线性复杂度的精确匹配。进行了大量的实验来评估合成和现实世界的数据集，这说明我们的算法优于暴力方法和多尺度表示的多步骤过滤机制MSM。

##### URL
[http://arxiv.org/abs/1710.10088](http://arxiv.org/abs/1710.10088)

