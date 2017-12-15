---
layout: post
title: "Policy Networks with Two-Stage Training for Dialogue Systems"
date: 2016-09-12 16:23:42
categories: arXiv_CL
tags: arXiv_CL Knowledge Tracking Reinforcement_Learning
author: Mehdi Fatemi, Layla El Asri, Hannes Schulz, Jing He, Kaheer Suleman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to use deep policy networks which are trained with an advantage actor-critic method for statistically optimised dialogue systems. First, we show that, on summary state and action spaces, deep Reinforcement Learning (RL) outperforms Gaussian Processes methods. Summary state and action spaces lead to good performance but require pre-engineering effort, RL knowledge, and domain expertise. In order to remove the need to define such summary spaces, we show that deep RL can also be trained efficiently on the original state and action spaces. Dialogue systems based on partially observable Markov decision processes are known to require many dialogues to train, which makes them unappealing for practical deployment. We show that a deep RL method based on an actor-critic architecture can exploit a small amount of data very efficiently. Indeed, with only a few hundred dialogues collected with a handcrafted policy, the actor-critic deep learner is considerably bootstrapped from a combination of supervised and batch RL. In addition, convergence to an optimal policy is significantly sped up compared to other deep RL methods initialized on the data with batch RL. All experiments are performed on a restaurant domain derived from the Dialogue State Tracking Challenge 2 (DSTC2) dataset.

##### Abstract (translated by Google)
在本文中，我们建议使用深度策略网络，训练有利于优化对话系统的优化评论者方法。首先，我们表明，在概括的状态和动作空间中，深度强化学习（RL）优于高斯过程方法。总结状态和动作空间导致良好的性能，但需要预先设计工作，RL知识和领域专业知识。为了消除定义这样的汇总空间的需要，我们显示深度RL也可以有效地训练原始状态和动作空间。基于部分可观察马尔可夫决策过程的对话系统已知需要许多对话来训练，这使得它们在实际部署中不具有吸引力。我们表明，基于演员 - 评论者架构的深度RL方法可以非常有效地利用少量的数据。事实上，只有几百个手工制作的对话被收集，演员 - 评论家深度学习者从监督和批量RL的组合中被大大地引导。另外，与其他RL批量数据初始化的深度RL方法相比，最优策略的收敛速度显着加快。所有的实验都是在对话状态追踪挑战2（DSTC2）数据集中得到的一个餐馆域上进行的。

##### URL
[https://arxiv.org/abs/1606.03152](https://arxiv.org/abs/1606.03152)

##### PDF
[https://arxiv.org/pdf/1606.03152](https://arxiv.org/pdf/1606.03152)

