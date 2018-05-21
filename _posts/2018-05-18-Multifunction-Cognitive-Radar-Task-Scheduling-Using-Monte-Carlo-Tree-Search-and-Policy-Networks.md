---
layout: post
title: "Multifunction Cognitive Radar Task Scheduling Using Monte Carlo Tree Search and Policy Networks"
date: 2018-05-18 06:58:16
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Mahdi Shaghaghi, Raviraj S. Adve, Zhen Ding
mathjax: true
---

* content
{:toc}

##### Abstract
A modern radar may be designed to perform multiple functions, such as surveillance, tracking, and fire control. Each function requires the radar to execute a number of transmit-receive tasks. A radar resource management (RRM) module makes decisions on parameter selection, prioritization, and scheduling of such tasks. RRM becomes especially challenging in overload situations, where some tasks may need to be delayed or even dropped. In general, task scheduling is an NP-hard problem. In this work, we develop the branch-and-bound (B&amp;B) method which obtains the optimal solution but at exponential computational complexity. On the other hand, heuristic methods have low complexity but provide relatively poor performance. We resort to machine learning-based techniques to address this issue; specifically we propose an approximate algorithm based on the Monte Carlo tree search method. Along with using bound and dominance rules to eliminate nodes from the search tree, we use a policy network to help to reduce the width of the search. Such a network can be trained using solutions obtained by running the B&amp;B method offline on problems with feasible complexity. We show that the proposed method provides near-optimal performance, but with computational complexity orders of magnitude smaller than the B&amp;B algorithm.

##### Abstract (translated by Google)
现代雷达可以设计为执行多种功能，例如监视，跟踪和火控。每个功能都需要雷达执行一些发送 - 接收任务。雷达资源管理（RRM）模块决定参数选择，优先级排序和这些任务的调度。 RRM在超负荷的情况下变得尤其具有挑战性，在这种情况下，某些任务可能需要延迟甚至下降。一般来说，任务调度是一个NP难题。在这项工作中，我们开发了分支定界（B＆amp; B）方法，该方法获得最优解，但是指数计算复杂度较高。另一方面，启发式方法复杂度低，但性能相对较差。我们采用基于机器学习的技术来解决这个问题。具体而言，我们提出了一种基于蒙特卡罗树搜索方法的近似算法。除了使用绑定和优势规则来消除搜索树中的节点外，我们还使用策略网络来帮助减少搜索的宽度。这样的网络可以使用通过将B＆amp; B方法离线运行而获得的解决方案用可行复杂性的问题进行训练。我们表明，所提出的方法提供接近最佳的性能，但是具有比B＆amp; B算法小的计算复杂度数量级。

##### URL
[http://arxiv.org/abs/1805.07069](http://arxiv.org/abs/1805.07069)

##### PDF
[http://arxiv.org/pdf/1805.07069](http://arxiv.org/pdf/1805.07069)

