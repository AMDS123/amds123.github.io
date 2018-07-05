---
layout: post
title: "Region Growing Curriculum Generation for Reinforcement Learning"
date: 2018-07-04 01:49:29
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning
author: Artem Molchanov, Karol Hausman, Stan Birchfield, Gaurav Sukhatme
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a policy capable of moving an agent between any two states in the environment is important for many robotics problems involving navigation and manipulation. Due to the sparsity of rewards in such tasks, applying reinforcement learning in these scenarios can be challenging. Common approaches for tackling this problem include reward engineering with auxiliary rewards, requiring domain-specific knowledge or changing the objective. 
 In this work, we introduce a method based on region-growing that allows learning in an environment with any pair of initial and goal states. Our algorithm first learns how to move between nearby states and then increases the difficulty of the start-goal transitions as the agent's performance improves. This approach creates an efficient curriculum for learning the objective behavior of reaching any goal from any initial state. In addition, we describe a method to adaptively adjust expansion of the growing region that allows automatic adjustment of the key exploration hyperparameter to environments with different requirements. We evaluate our approach on a set of simulated navigation and manipulation tasks, where we demonstrate that our algorithm can efficiently learn a policy in the presence of sparse rewards.

##### Abstract (translated by Google)
学习能够在环境中的任何两个状态之间移动代理的策略对于涉及导航和操纵的许多机器人问题是重要的。由于此类任务中奖励的稀疏性，在这些情景中应用强化学习可能具有挑战性。解决此问题的常用方法包括使用辅助奖励进行奖励工程，需要特定领域知识或更改目标。
 在这项工作中，我们引入了一种基于区域增长的方法，该方法允许在具有任何初始状态和目标状态的环境中进行学习。我们的算法首先学习如何在附近状态之间移动，然后随着代理的性能提高而增加起始目标转换的难度。这种方法创造了一个有效的课程，用于学习从任何初始状态到达任何目标的客观行为。此外，我们描述了一种自适应调整生长区域扩展的方法，该方法允许将关键探索超参数自动调整到具有不同要求的环境。我们在一组模拟导航和操作任务上评估我们的方法，其中我们证明我们的算法可以在稀疏奖励的情况下有效地学习策略。

##### URL
[http://arxiv.org/abs/1807.01425](http://arxiv.org/abs/1807.01425)

##### PDF
[http://arxiv.org/pdf/1807.01425](http://arxiv.org/pdf/1807.01425)

