---
layout: post
title: "Efficient Splitting-based Method for Global Image Smoothing"
date: 2016-04-26 14:05:41
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Youngjung Kim, Dongbo Min, Bumsub Ham, Kwanghoon Sohn
mathjax: true
---

* content
{:toc}

##### Abstract
Edge-preserving smoothing (EPS) can be formulated as minimizing an objective function that consists of data and prior terms. This global EPS approach shows better smoothing performance than a local one that typically has a form of weighted averaging, at the price of high computational cost. In this paper, we introduce a highly efficient splitting-based method for global EPS that minimizes the objective function of ${l_2}$ data and prior terms (possibly non-smooth and non-convex) in linear time. Different from previous splitting-based methods that require solving a large linear system, our approach solves an equivalent constrained optimization problem, resulting in a sequence of 1D sub-problems. This enables linear time solvers for weighted-least squares and -total variation problems. Our solver converges quickly, and its runtime is even comparable to state-of-the-art local EPS approaches. We also propose a family of fast iteratively re-weighted algorithms using a non-convex prior term. Experimental results demonstrate the effectiveness and flexibility of our approach in a range of computer vision and image processing tasks.

##### Abstract (translated by Google)
边缘保持平滑（EPS）可以被表述为最小化由数据和先验项组成的目标函数。这种全球EPS方法比以本地方式为代表的加权平均方式具有更好的平滑性能，其代价是计算成本高。在本文中，我们引入了一种高效的基于全球EPS的分裂方法，使线性时间内$ {l_2} $ data和先验项（可能是非光滑的和非凸的）的目标函数最小化。不同于以往基于分裂的方法，需要求解一个大的线性系统，我们的方法解决了一个等价的约束优化问题，导致一系列的一维子问题。这使得线性时间求解器可用于加权最小二乘和总变差问题。我们的解算器能够快速收敛，其运行时间甚至可与当前最先进的本地EPS方法相媲美。我们还提出了一个使用非凸前项的快速迭代重加权算法族。实验结果证明了我们的方法在一系列计算机视觉和图像处理任务中的有效性和灵活性。

##### URL
[https://arxiv.org/abs/1604.07681](https://arxiv.org/abs/1604.07681)

##### PDF
[https://arxiv.org/pdf/1604.07681](https://arxiv.org/pdf/1604.07681)

