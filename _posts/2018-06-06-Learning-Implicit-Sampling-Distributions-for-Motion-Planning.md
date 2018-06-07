---
layout: post
title: "Learning Implicit Sampling Distributions for Motion Planning"
date: 2018-06-06 00:23:54
categories: arXiv_RO
tags: arXiv_RO
author: Clark Zhang, Jinwook Huh, Daniel D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Sampling-based motion planners have experienced much success due to their ability to efficiently and evenly explore the state space. However, for many tasks, it may be more efficient to not uniformly explore the state space, especially when there is prior information about its structure. Previous methods have attempted to modify the sampling distribution using hand selected heuristics that can work well for specific environments but not universally. In this paper, a policy- search based method is presented as an adaptive way to learn implicit sampling distributions for different environments. It utilizes information from past searches in similar environments to generate better distributions in novel environments, thus reducing overall computational cost. Our method can be incor- porated with a variety of sampling-based planners to improve performance. Our approach is validated on a number of tasks, including a 7DOF robot arm, showing marked improvement in number of collision checks as well as number of nodes expanded compared with baseline methods.

##### Abstract (translated by Google)
基于采样的运动规划人员由于能够高效均匀地探索状态空间而获得了巨大的成功。然而，对于许多任务来说，不统一探索状态空间可能更有效，特别是当有关于结构的先验信息时。以前的方法试图使用手选启发式来修改采样分布，这对于特定的环境可以很好地工作，但不是普遍的。在本文中，基于策略搜索的方法被呈现为学习不同环境的隐式采样分布的自适应方式。它利用来自类似环境中过去搜索的信息，在新环境中生成更好的分布，从而降低总体计算成本。我们的方法可以与各种基于抽样的规划师结合使用，以提高性能。我们的方法经过多项任务的验证，其中包括7DOF机器人手臂，与基准方法相比，碰撞检查次数显着增加，节点数量也有所增加。

##### URL
[http://arxiv.org/abs/1806.01968](http://arxiv.org/abs/1806.01968)

##### PDF
[http://arxiv.org/pdf/1806.01968](http://arxiv.org/pdf/1806.01968)

