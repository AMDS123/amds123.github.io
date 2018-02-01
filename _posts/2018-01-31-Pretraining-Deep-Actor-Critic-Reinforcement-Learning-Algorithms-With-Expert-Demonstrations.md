---
layout: post
title: "Pretraining Deep Actor-Critic Reinforcement Learning Algorithms With Expert Demonstrations"
date: 2018-01-31 14:30:00
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Xiaoqin Zhang, Huimin Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Pretraining with expert demonstrations have been found useful in speeding up the training process of deep reinforcement learning algorithms since less online simulation data is required. Some people use supervised learning to speed up the process of feature learning, others pretrain the policies by imitating expert demonstrations. However, these methods are unstable and not suitable for actor-critic reinforcement learning algorithms. Also, some existing methods rely on the global optimum assumption, which is not true in most scenarios. In this paper, we employ expert demonstrations in a actor-critic reinforcement learning framework, and meanwhile ensure that the performance is not affected by the fact that expert demonstrations are not global optimal. We theoretically derive a method for computing policy gradients and value estimators with only expert demonstrations. Our method is theoretically plausible for actor-critic reinforcement learning algorithms that pretrains both policy and value functions. We apply our method to two of the typical actor-critic reinforcement learning algorithms, DDPG and ACER, and demonstrate with experiments that our method not only outperforms the RL algorithms without pretraining process, but also is more simulation efficient.

##### Abstract (translated by Google)
由于较少的在线仿真数据是必需的，已经发现通过专家演示预训练加快了深度强化学习算法的训练过程。有些人使用监督式学习来加速特征学习的过程，另外一些人则通过模仿专家示威来预先制定政策。然而，这些方法是不稳定的，不适合演员评论者强化学习算法。而且，一些现有的方法依赖于全局最优假设，在大多数情况下这是不正确的。在本文中，我们在一个评论者强化学习框架中采用专家演示，同时确保演示不受专家演示不是全局最优的事实的影响。我们从理论上推导出一种只用专家演示来计算策略梯度和价值估计的方法。我们的方法在理论上是可行的，演员 - 评论者强化学习算法可以预演政策和价值功能。我们将这种方法应用于两种典型的动作评论者强化学习算法DDPG和ACER，并通过实验证明，我们的方法不仅不需要预训练就能胜过RL算法，而且更具仿真效率。

##### URL
[http://arxiv.org/abs/1801.10459](http://arxiv.org/abs/1801.10459)

##### PDF
[http://arxiv.org/pdf/1801.10459](http://arxiv.org/pdf/1801.10459)

