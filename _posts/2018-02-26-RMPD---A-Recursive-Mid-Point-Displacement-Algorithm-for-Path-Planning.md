---
layout: post
title: "RMPD - A Recursive Mid-Point Displacement Algorithm for Path Planning"
date: 2018-02-26 01:31:52
categories: arXiv_RO
tags: arXiv_RO
author: Fangda Li, Ankit V. Manerikar, Avinash C. Kak
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by what is required for real-time path planning, the paper starts out by presenting sRMPD, a new recursive "local" planner founded on the key notion that, unless made necessary by an obstacle, there must be no deviation from the shortest path between any two points, which would normally be a straight line path in the configuration space. Subsequently, we increase the power of sRMPD by using it as a "connect" subroutine call in a higher-level sampling-based algorithm mRMPD that is inspired by multi-RRT. As a consequence, mRMPD spawns a larger number of space exploring trees in regions of the configuration space that are characterized by a higher density of obstacles. The overall effect is a hybrid tree growing strategy with a trade-off between random exploration as made possible by multi-RRT based logic and immediate exploitation of opportunities to connect two states as made possible by sRMPD. The mRMPD planner can be biased with regard to this trade-off for solving different kinds of planning problems efficiently. Based on the test cases we have run, our experiments show that mRMPD can reduce planning time by up to 80% compared to basic RRT.

##### Abstract (translated by Google)
受到实时路径规划所要求的启发，本文首先介绍了sRMPD，这是一种新的递归“本地”规划者，它基于这样一个关键概念，除非有必要通过障碍物，否则必须不偏离最短路径在任何两点之间，这通常是配置空间中的直线路径。随后，我们增加了sRMPD的功能，将其作为一个“连接”子程序调用，采用基于多RRT启发的高级采样算法mRMPD。因此，mRMPD在配置空间中以更高密度的障碍为特征的区域中产生了更多的空间探索树。整体效果是一种混合型树木增长策略，在多RRT基础逻辑可能实现的随机探测与通过sRMPD实现两个状态连接的机会之间进行权衡。 mRMPD计划人员可能会为了有效解决不同类型的计划问题而在这种权衡方面存在偏差。根据我们运行的测试案例，我们的实验表明，与基本RRT相比，mRMPD可以将计划时间缩短多达80％。

##### URL
[http://arxiv.org/abs/1709.00488](http://arxiv.org/abs/1709.00488)

##### PDF
[http://arxiv.org/pdf/1709.00488](http://arxiv.org/pdf/1709.00488)

