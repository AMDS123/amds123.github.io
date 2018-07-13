---
layout: post
title: "A Constrained Randomized Shortest-Paths Framework for Optimal Exploration"
date: 2018-07-12 11:42:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Bertrand Lebichot, Guillaume Guex, Ilkka Kivim&#xe4;ki, Marco Saerens
mathjax: true
---

* content
{:toc}

##### Abstract
The present work extends the randomized shortest-paths framework (RSP), interpolating between shortest-path and random-walk routing in a network, in three directions. First, it shows how to deal with equality constraints on a subset of transition probabilities and develops a generic algorithm for solving this constrained RSP problem using Lagrangian duality. Second, it derives a surprisingly simple iterative procedure to compute the optimal, randomized, routing policy generalizing the previously developed "soft" Bellman-Ford algorithm. The resulting algorithm allows balancing exploitation and exploration in an optimal way by interpolating between a pure random behavior and the deterministic, optimal, policy (least-cost paths) while satisfying the constraints. Finally, the two algorithms are applied to Markov decision problems by considering the process as a constrained RSP on a bipartite state-action graph. In this context, the derived "soft" value iteration algorithm appears to be closely related to dynamic policy programming as well as Kullback-Leibler and path integral control, and similar to a recently introduced reinforcement learning exploration strategy. This shows that this strategy is optimal in the RSP sense - it minimizes expected path cost subject to relative entropy constraint. Simulation results on illustrative examples show that the model behaves as expected.

##### Abstract (translated by Google)
目前的工作扩展了随机最短路径框架（RSP），在三个方向上在网络中的最短路径和随机行走路由之间进行插值。首先，它展示了如何处理转移概率子集上的等式约束，并开发了一个使用拉格朗日对偶性来解决这个约束RSP问题的通用算法。其次，它得出了一个令人惊讶的简单迭代过程来计算最优的随机路由策略，该策略推广了先前开发的“软”Bellman-Ford算法。由此产生的算法允许通过在满足约束的同时在纯随机行为和确定性最优策略（最低成本路径）之间进行插值来以最佳方式平衡利用和探索。最后，通过将该过程视为二分状态 - 动作图上的约束RSP，将这两种算法应用于马尔可夫决策问题。在这种情况下，派生的“软”值迭代算法似乎与动态策略编程以及Kullback-Leibler和路径积分控制密切相关，并且类似于最近引入的强化学习探索策略。这表明该策略在RSP意义上是最优的 - 它最小化了受相对熵约束的预期路径成本。对说明性示例的仿真结果表明该模型表现得如预期的那样。

##### URL
[http://arxiv.org/abs/1807.04551](http://arxiv.org/abs/1807.04551)

##### PDF
[http://arxiv.org/pdf/1807.04551](http://arxiv.org/pdf/1807.04551)

