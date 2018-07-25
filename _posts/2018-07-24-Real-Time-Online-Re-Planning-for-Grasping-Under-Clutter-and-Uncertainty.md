---
layout: post
title: "Real-Time Online Re-Planning for Grasping Under Clutter and Uncertainty"
date: 2018-07-24 11:37:13
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Wisdom C. Agboh, Mehmet R. Dogar
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of grasping in clutter. While there have been motion planners developed to address this problem in recent years, these planners are mostly tailored for open-loop execution. Open-loop execution in this domain, however, is likely to fail, since it is not possible to model the dynamics of the multi-body multi-contact physical system with enough accuracy, neither is it reasonable to expect robots to know the exact physical properties of objects, such as frictional, inertial, and geometrical. Therefore, we propose an online re-planning approach for grasping through clutter. The main challenge is the long planning times this domain requires, which makes fast re-planning and fluent execution difficult to realize. In order to address this, we propose an easily parallelizable stochastic trajectory optimization based algorithm that generates a sequence of optimal controls. We show that by running this optimizer only for a small number of iterations, it is possible to perform real time re-planning cycles to achieve reactive manipulation under clutter and uncertainty.

##### Abstract (translated by Google)
我们考虑抓住杂乱的问题。虽然近年来已经开发出用于解决该问题的运动规划器，但这些规划器大多是为开环执行而定制的。然而，该领域的开环执行可能会失败，因为不可能以足够的精度对多体多接触物理系统的动态建模，也不能期望机器人知道确切的物理物体的属性，例如摩擦力，惯性力和几何形状。因此，我们提出了一种在线重新规划方法，以便掌握杂乱。主要挑战是该领域需要的漫长规划时间，这使得快速重新规划和流畅执行难以实现。为了解决这个问题，我们提出了一种易于并行化的基于随机轨迹优化的算法，该算法可以生成一系列最优控制。我们表明，通过仅针对少量迭代运行此优化器，可以执行实时重新规划周期，以在杂乱和不确定性下实现反应性操作。

##### URL
[http://arxiv.org/abs/1807.09049](http://arxiv.org/abs/1807.09049)

##### PDF
[http://arxiv.org/pdf/1807.09049](http://arxiv.org/pdf/1807.09049)

