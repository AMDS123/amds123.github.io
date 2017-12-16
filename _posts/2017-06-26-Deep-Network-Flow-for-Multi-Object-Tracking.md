---
layout: post
title: "Deep Network Flow for Multi-Object Tracking"
date: 2017-06-26 17:08:45
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking
author: Samuel Schulter, Paul Vernaza, Wongun Choi, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Data association problems are an important component of many computer vision applications, with multi-object tracking being one of the most prominent examples. A typical approach to data association involves finding a graph matching or network flow that minimizes a sum of pairwise association costs, which are often either hand-crafted or learned as linear functions of fixed features. In this work, we demonstrate that it is possible to learn features for network-flow-based data association via backpropagation, by expressing the optimum of a smoothed network flow problem as a differentiable function of the pairwise association costs. We apply this approach to multi-object tracking with a network flow formulation. Our experiments demonstrate that we are able to successfully learn all cost functions for the association problem in an end-to-end fashion, which outperform hand-crafted costs in all settings. The integration and combination of various sources of inputs becomes easy and the cost functions can be learned entirely from data, alleviating tedious hand-designing of costs.

##### Abstract (translated by Google)
数据关联问题是许多计算机视觉应用的重要组成部分，多目标跟踪是最突出的例子之一。数据关联的典型方法涉及寻找图形匹配或网络流量，以最小化成对关联成本的总和，其通常是手工制造的或学习为固定特征的线性函数。在这项工作中，我们证明了通过反向传播学习可以学习基于网络流量的数据关联的特征，通过将平滑网络流量问题的最优化表达为成对关联成本的可微函数。我们将这种方法应用于网络流量制定的多对象跟踪。我们的实验表明，我们能够以端到端的方式成功学习关联问题的所有成本函数，这在所有设置中都胜过手工成本。各种输入源的集成和组合变得简单，成本函数可以完全从数据中学习，减轻了繁琐的成本手工设计。

##### URL
[https://arxiv.org/abs/1706.08482](https://arxiv.org/abs/1706.08482)

##### PDF
[https://arxiv.org/pdf/1706.08482](https://arxiv.org/pdf/1706.08482)

