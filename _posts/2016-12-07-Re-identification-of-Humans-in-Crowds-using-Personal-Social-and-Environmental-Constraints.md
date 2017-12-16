---
layout: post
title: "Re-identification of Humans in Crowds using Personal, Social and Environmental Constraints"
date: 2016-12-07 09:03:11
categories: arXiv_CV
tags: arXiv_CV Re-identification Optimization
author: Shayan Modiri Assari, Haroon Idrees, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of human re-identification across non-overlapping cameras in crowds.Re-identification in crowded scenes is a challenging problem due to large number of people and frequent occlusions, coupled with changes in their appearance due to different properties and exposure of cameras. To solve this problem, we model multiple Personal, Social and Environmental (PSE) constraints on human motion across cameras. The personal constraints include appearance and preferred speed of each individual assumed to be similar across the non-overlapping cameras. The social influences (constraints) are quadratic in nature, i.e. occur between pairs of individuals, and modeled through grouping and collision avoidance. Finally, the environmental constraints capture the transition probabilities between gates (entrances / exits) in different cameras, defined as multi-modal distributions of transition time and destination between all pairs of gates. We incorporate these constraints into an energy minimization framework for solving human re-identification. Assigning $1-1$ correspondence while modeling PSE constraints is NP-hard. We present a stochastic local search algorithm to restrict the search space of hypotheses, and obtain $1-1$ solution in the presence of linear and quadratic PSE constraints. Moreover, we present an alternate optimization using Frank-Wolfe algorithm that solves the convex approximation of the objective function with linear relaxation on binary variables, and yields an order of magnitude speed up over stochastic local search with minor drop in performance. We evaluate our approach using Cumulative Matching Curves as well $1-1$ assignment on several thousand frames of Grand Central, PRID and DukeMTMC datasets, and obtain significantly better results compared to existing re-identification methods.

##### Abstract (translated by Google)
本文针对人群中非重叠摄像机重新识别人的问题，由于人数众多，频繁遮挡，加上外观因不同性质和曝光而出现的变化，在拥挤的场景中重新识别是一个具有挑战性的问题的相机。为了解决这个问题，我们建立了多个个人，社会和环境（PSE）在摄像机上的人体运动约束。个人约束包括假设在非重叠摄像机中相似的每个个体的外观和优选速度。社会影响（约束）本质上是二次的，即发生在成对的个体之间，并通过分组和避免碰撞来建模。最后，环境约束捕获不同摄像机的门（入口/出口）之间的转换概率，定义为所有对门之间转换时间和目的地的多模态分布。我们将这些约束纳入能量最小化框架来解决人类重新识别问题。在建模PSE约束时分配$ 1-1 $对应关系是NP难题。我们提出了一个随机局部搜索算法来限制假设的搜索空间，并且在存在线性和二次PSE约束的情况下获得$ 1-1 $解。此外，我们使用Frank-Wolfe算法提出了一种替代优化方法，该方法通过对二元变量的线性松弛求解目标函数的凸近似，并且在随机局部搜索的情况下产生一个数量级的加速，而性能略有下降。我们使用累积匹配曲线以及在Grand Central，PRID和DukeMMC数据集的数千帧上评估我们的方法，并获得比现有的重新识别方法显着更好的结果。

##### URL
[https://arxiv.org/abs/1612.02155](https://arxiv.org/abs/1612.02155)

##### PDF
[https://arxiv.org/pdf/1612.02155](https://arxiv.org/pdf/1612.02155)

