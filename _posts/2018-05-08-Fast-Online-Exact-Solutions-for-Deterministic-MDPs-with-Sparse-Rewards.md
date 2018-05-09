---
layout: post
title: "Fast Online Exact Solutions for Deterministic MDPs with Sparse Rewards"
date: 2018-05-08 00:12:43
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Joshua R. Bertram, Xuxi Yang, Peng Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Markov Decision Processes (MDPs) are a mathematical framework for modeling sequential decision making under uncertainty. The classical approaches for solving MDPs are well known and have been widely studied, some of which rely on approximation techniques to solve MDPs with large state space and/or action space. However, most of these classical solution approaches and their approximation techniques still take much computation time to converge and usually must be re-computed if the reward function is changed. This paper introduces a novel alternative approach for exactly and efficiently solving deterministic, continuous MDPs with sparse reward sources. When the environment is such that the "distance" between states can be determined in constant time, e.g. grid world, our algorithm offers $O( |R|^2 \times |A|^2 \times |S|)$, where $|R|$ is the number of reward sources, $|A|$ is the number of actions, and $|S|$ is the number of states. Memory complexity for the algorithm is $O( |S| + |R| \times |A|)$. This new approach opens new avenues for boosting computational performance for certain classes of MDPs and is of tremendous value for MDP applications such as robotics and unmanned systems. This paper describes the algorithm and presents numerical experiment results to demonstrate its powerful computational performance. We also provide rigorous mathematical description of the approach.

##### Abstract (translated by Google)
马尔可夫决策过程（MDPs）是一个数学框架，用于模拟不确定条件下的顺序决策。用于解决MDP的经典方法是众所周知的并且已经被广泛研究，其中一些依赖于近似技术来解决具有大状态空间和/或动作空间的MDP。然而，大多数这些经典的解决方案和它们的逼近技术仍然需要大量的计算时间来收敛，并且如果奖励函数改变，通常必须重新计算。本文介绍了一种新颖的替代方法，用于精确有效地求解具有稀疏回报源的确定性连续MDP。当环境使得状态之间的“距离”可以在恒定时间内确定时，例如，我们的算法提供$ O（| R | ^ 2 \ times | A | ^ 2 \ times | S |）$，其中$ | R | $是奖励源的数量，$ | A | $是数字的行为，并且$ | S | $是状态的数量。该算法的内存复杂度为$ O（| S | + | R | \ times | A |）$。这种新方法为提高某些类别MDP的计算性能开辟了新的途径，对MDP应用（如机器人技术和无人系统）具有巨大的价值。本文描述了该算法，并给出了数值实验结果来展示其强大的计算性能。我们还提供严格的数学方法描述。

##### URL
[https://arxiv.org/abs/1805.02785](https://arxiv.org/abs/1805.02785)

##### PDF
[https://arxiv.org/pdf/1805.02785](https://arxiv.org/pdf/1805.02785)

