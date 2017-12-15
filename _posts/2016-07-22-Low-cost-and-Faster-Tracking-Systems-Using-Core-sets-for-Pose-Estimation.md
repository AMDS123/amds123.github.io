---
layout: post
title: "Low-cost and Faster Tracking Systems Using Core-sets for Pose-Estimation"
date: 2016-07-22 12:43:28
categories: arXiv_CV
tags: arXiv_CV Tracking Drone
author: Soliman Nasser, Ibrahim Jubran, Dan Feldman
mathjax: true
---

* content
{:toc}

##### Abstract
In the pose-estimation problem we need to align a set of $n$ markers (points in 3D space) and choose one of their n! permutations, so that the sum of squared corresponding distances to another ordered set of $n$ markers is minimized. We prove that every set has a weighted subset (core-set) of constant size (independent of $n$), such that computing the optimal orientation of the small core-set would yield exactly the same result as using the full set of $n$ markers. A deterministic algorithm for computing this core-set in $O(n)$ time is provided, using the Caratheodory Theorem from computational geometry. We can then boost the performance of inefficient algorithms or popular heuristics (such as ICP) by running them (maybe many times) on our small coreset. Based on this coreset, we developed a low-cost ($<\$100$) real-time tracking system. As an example application, we turn a toy quadcopter ($<\$20$) with no sensors into an "autonomous drone" that is controlled by a mini-computer ($<\$30)$. Experimental results show that, unlike uniform sampling of features, our suggested coreset yields error that is comparable to commercial ($>\$10,000$) tracking systems for such simple but common applications. Open source code is provided.

##### Abstract (translated by Google)
在姿态估计问题中，我们需要对齐一组$ n $标记（三维空间中的点）并选择它们中的一个！置换，从而将与另一有序的$ n $标记集的相应距离的平方和最小化。我们证明了每一个集合都有一个恒定大小（独立于$ n $）的加权子集（核心集合），这样计算小核心集合的最优方向将产生与使用完整集合$完全相同的结果n $标记。提供了一个用$ O（n）$ time计算这个核心集合的确定性算法，使用计算几何中的Caratheodory定理。然后，我们可以通过在我们的小型核心集上运行它们（可能很多次）来提升低效算法或流行启发式算法（如ICP）的性能。基于这个核心，我们开发了一个低成本（$ <$ 100 $）的实时跟踪系统。作为一个应用例子，我们把一个没有传感器的玩具quadcopter（$ <$ $ $ $ $ $）变成一个由微型计算机（$ <$ $ 30）$控制的“自主式无人机”。实验结果表明，与统一的特征采样不同，我们建议的核心集合产生的误差与商业（$> $ 10,000 $）跟踪系统的误差相当，用于这种简单但常见的应用。提供开源代码。

##### URL
[https://arxiv.org/abs/1511.09120](https://arxiv.org/abs/1511.09120)

##### PDF
[https://arxiv.org/pdf/1511.09120](https://arxiv.org/pdf/1511.09120)

