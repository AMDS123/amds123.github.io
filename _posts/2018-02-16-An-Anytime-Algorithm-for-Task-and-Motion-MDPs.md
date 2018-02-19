---
layout: post
title: "An Anytime Algorithm for Task and Motion MDPs"
date: 2018-02-16 04:52:58
categories: arXiv_AI
tags: arXiv_AI
author: Siddharth Srivastava, Nishant Desai, Richard Freedman, Shlomo Zilberstein
mathjax: true
---

* content
{:toc}

##### Abstract
Integrated task and motion planning has emerged as a challenging problem in sequential decision making, where a robot needs to compute high-level strategy and low-level motion plans for solving complex tasks. While high-level strategies require decision making over longer time-horizons and scales, their feasibility depends on low-level constraints based upon the geometries and continuous dynamics of the environment. The hybrid nature of this problem makes it difficult to scale; most existing approaches focus on deterministic, fully observable scenarios. We present a new approach where the high-level decision problem occurs in a stochastic setting and can be modeled as a Markov decision process. In contrast to prior efforts, we show that complete MDP policies, or contingent behaviors, can be computed effectively in an anytime fashion. Our algorithm continuously improves the quality of the solution and is guaranteed to be probabilistically complete. We evaluate the performance of our approach on a challenging, realistic test problem: autonomous aircraft inspection. Our results show that we can effectively compute consistent task and motion policies for the most likely execution-time outcomes using only a fraction of the computation required to develop the complete task and motion policy.

##### Abstract (translated by Google)
集成任务和运动规划已经成为顺序决策中的一个具有挑战性的问题，机器人需要计算高层战略和低层运动计划来解决复杂的任务。虽然高层战略需要在较长的时间范围和规模上作出决策，但其可行性取决于基于环境的几何形状和连续动态的低层约束。这个问题的混合性使得难以扩展;大多数现有的方法都着眼于确定性的，完全可观察的情景。我们提出了一种新的方法，其中高层决策问题出现在随机设置中，并且可以建模为马尔可夫决策过程。与之前的工作相比，我们表明可以随时有效地计算完整的MDP策略或者随机行为。我们的算法不断提高解决方案的质量，并保证概率性地完成。我们评估我们的方法在具有挑战性的，现实的测试问题上的性能：自主飞机检查。我们的研究结果表明，我们可以使用开发完整任务和运动策略所需的一小部分计算，为最可能的执行时间结果有效计算一致的任务和运动策略。

##### URL
[https://arxiv.org/abs/1802.05835](https://arxiv.org/abs/1802.05835)

##### PDF
[https://arxiv.org/pdf/1802.05835](https://arxiv.org/pdf/1802.05835)

