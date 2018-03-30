---
layout: post
title: "Forward-Backward Reinforcement Learning"
date: 2018-03-27 04:33:08
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning
author: Ashley D. Edwards, Laura Downs, James C. Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
Goals for reinforcement learning problems are typically defined through hand-specified rewards. To design such problems, developers of learning algorithms must inherently be aware of what the task goals are, yet we often require agents to discover them on their own without any supervision beyond these sparse rewards. While much of the power of reinforcement learning derives from the concept that agents can learn with little guidance, this requirement greatly burdens the training process. If we relax this one restriction and endow the agent with knowledge of the reward function, and in particular of the goal, we can leverage backwards induction to accelerate training. To achieve this, we propose training a model to learn to take imagined reversal steps from known goal states. Rather than training an agent exclusively to determine how to reach a goal while moving forwards in time, our approach travels backwards to jointly predict how we got there. We evaluate our work in Gridworld and Towers of Hanoi and empirically demonstrate that it yields better performance than standard DDQN.

##### Abstract (translated by Google)
强化学习问题的目标通常通过手工指定的奖励来定义。为了设计这样的问题，学习算法的开发者必须内在地意识到任务目标是什么，然而我们经常要求代理人自己发现它们，除了这些稀疏奖励之外，没有任何监督。虽然强化学习的许多力量来自于行动者可以在很少指导下学习的概念，但这一要求极大地加重了培训过程。如果我们放松这一限制并赋予代理人奖励功能，特别是目标知识，我们可以利用向后感应来加速培训。为了实现这一目标，我们提出培训一个模型，学习从已知的目标状态中采取想象的逆转步骤。我们的方法不是专门培训代理人以确定如何在实现目标的同时前进，而是通过反向传播来共同预测我们到达目标的方式。我们评估我们在河内的Gridworld和Towers的工作，并凭经验证明它比标准的DDQN具有更好的性能。

##### URL
[https://arxiv.org/abs/1803.10227](https://arxiv.org/abs/1803.10227)

##### PDF
[https://arxiv.org/pdf/1803.10227](https://arxiv.org/pdf/1803.10227)

