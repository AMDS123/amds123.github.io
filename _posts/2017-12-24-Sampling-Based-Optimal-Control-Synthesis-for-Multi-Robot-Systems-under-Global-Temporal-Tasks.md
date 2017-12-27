---
layout: post
title: "Sampling-Based Optimal Control Synthesis for Multi-Robot Systems under Global Temporal Tasks"
date: 2017-12-24 13:41:28
categories: arXiv_RO
tags: arXiv_RO
author: Yiannis Kantaros, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new optimal control synthesis algorithm for multi-robot systems under global temporal logic tasks. Existing planning approaches under global temporal goals rely on graph search techniques applied to a product automaton constructed among the robots. In this paper, we propose a new sampling-based algorithm that builds incrementally trees that approximate the state-space and transitions of the synchronous product automaton. By approximating the product automaton by a tree rather than representing it explicitly, we require much fewer memory resources to store it and motion plans can be found by tracing sequences of parent nodes without the need for sophisticated graph search methods. This significantly increases the scalability of our algorithm compared to existing optimal control synthesis methods. We also show that the proposed algorithm is probabilistically complete and asymptotically optimal. Finally, we present numerical experiments showing that our approach can synthesize optimal plans from product automata with billions of states, which is not possible using standard optimal control synthesis algorithms or model checkers.

##### Abstract (translated by Google)
本文提出了一种全局时间逻辑任务下多机器人系统的最优控制综合算法。全球时间目标下的现有规划方法依赖于图形搜索技术应用于机器人之间构建的产品自动机。在本文中，我们提出了一种新的基于抽样的算法，该算法增量式地构建近似于同步积自动机的状态空间和过渡的树。通过用树近似产品自动机而不是明确地表示，我们需要更少的存储资源来存储它，并且可以通过追踪父节点的序列来找到运动计划，而不需要复杂的图搜索方法。与现有的最优控制合成方法相比，这显着增加了我们的算法的可扩展性。我们还表明，提出的算法是概率完备的渐近最优。最后，我们提出了数值实验，表明我们的方法可以从数十亿个状态的产品自动机中合成最优方案，这是使用标准最优控制综合算法或模型检验器所不可能的。

##### URL
[http://arxiv.org/abs/1706.04216](http://arxiv.org/abs/1706.04216)

##### PDF
[http://arxiv.org/pdf/1706.04216](http://arxiv.org/pdf/1706.04216)

