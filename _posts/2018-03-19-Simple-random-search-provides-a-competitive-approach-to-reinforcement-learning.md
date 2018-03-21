---
layout: post
title: "Simple random search provides a competitive approach to reinforcement learning"
date: 2018-03-19 17:35:14
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Horia Mania, Aurelia Guy, Benjamin Recht
mathjax: true
---

* content
{:toc}

##### Abstract
A common belief in model-free reinforcement learning is that methods based on random search in the parameter space of policies exhibit significantly worse sample complexity than those that explore the space of actions. We dispel such beliefs by introducing a random search method for training static, linear policies for continuous control problems, matching state-of-the-art sample efficiency on the benchmark MuJoCo locomotion tasks. Our method also finds a nearly optimal controller for a challenging instance of the Linear Quadratic Regulator, a classical problem in control theory, when the dynamics are not known. Computationally, our random search algorithm is at least 15 times more efficient than the fastest competing model-free methods on these benchmarks. We take advantage of this computational efficiency to evaluate the performance of our method over hundreds of random seeds and many different hyperparameter configurations for each benchmark task. Our simulations highlight a high variability in performance in these benchmark tasks, suggesting that commonly used estimations of sample efficiency do not adequately evaluate the performance of RL algorithms.

##### Abstract (translated by Google)
对无模型强化学习的一个普遍看法是，基于随机搜索策略的参数空间中的方法比那些探索行为空间的方法表现出明显更差的样本复杂性。我们通过引入一种随机搜索方法来消除这种信念，为连续控制问题提供静态，线性策略的培训，使基准MuJoCo运动任务的最新样本效率相匹配。我们的方法也找到了一个近乎最优的控制器，用于线性平方调节器的一个具有挑战性的实例，这是控制理论中的一个经典问题，当动态特性未知时。在计算上，我们的随机搜索算法比这些基准测试中最快的竞争无模型方法的效率至少高15倍。我们利用这种计算效率来评估我们的方法在数百个随机种子和许多不同的超参数配置下对每个基准任务的性能。我们的仿真强调了这些基准测试任务中性能的高度可变性，表明常用的样本效率估计并未充分评估RL算法的性能。

##### URL
[https://arxiv.org/abs/1803.07055](https://arxiv.org/abs/1803.07055)

##### PDF
[https://arxiv.org/pdf/1803.07055](https://arxiv.org/pdf/1803.07055)

