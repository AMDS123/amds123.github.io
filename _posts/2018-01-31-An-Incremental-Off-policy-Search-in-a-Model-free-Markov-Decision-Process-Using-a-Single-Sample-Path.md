---
layout: post
title: "An Incremental Off-policy Search in a Model-free Markov Decision Process Using a Single Sample Path"
date: 2018-01-31 02:53:34
categories: arXiv_AI
tags: arXiv_AI
author: Ajin George Joseph, Shalabh Bhatnagar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider a modified version of the control problem in a model free Markov decision process (MDP) setting with large state and action spaces. The control problem most commonly addressed in the contemporary literature is to find an optimal policy which maximizes the value function, i.e., the long run discounted reward of the MDP. The current settings also assume access to a generative model of the MDP with the hidden premise that observations of the system behaviour in the form of sample trajectories can be obtained with ease from the model. In this paper, we consider a modified version, where the cost function is the expectation of a non-convex function of the value function without access to the generative model. Rather, we assume that a sample trajectory generated using a priori chosen behaviour policy is made available. In this restricted setting, we solve the modified control problem in its true sense, i.e., to find the best possible policy given this limited information. We propose a stochastic approximation algorithm based on the well-known cross entropy method which is data (sample trajectory) efficient, stable, robust as well as computationally and storage efficient. We provide a proof of convergence of our algorithm to a policy which is globally optimal relative to the behaviour policy. We also present experimental results to corroborate our claims and we demonstrate the superiority of the solution produced by our algorithm compared to the state-of-the-art algorithms under appropriately chosen behaviour policy.

##### Abstract (translated by Google)
在本文中，我们考虑一个修改版本的控制问题在模型自由马尔可夫决策过程（MDP）设置与大的状态和行动空间。在当代文献中最常见的控制问题是找到最大化价值函数的最优策略，即MDP的长期贴现奖励。当前的设置也假定访问MDP的生成模型，其隐藏的前提是可以容易地从模型中获得以样本轨迹的形式观察系统行为。在本文中，我们考虑一个修改的版本，其中代价函数是值函数的非凸函数的期望，而不访问生成模型。相反，我们假设使用先验选择的行为策略生成的样本轨迹可用。在这个有限的环境中，我们解决了修改后的控制问题，也就是在这个有限的信息下找到最好的策略。我们提出了一个基于众所周知的交叉熵方法的随机近似算法，它是数据（样本轨迹）高效，稳定，鲁棒以及计算和存储效率高。我们提供了一个证明我们的算法与行为策略相关的全局最优策略的收敛性。我们还提出了实验结果来证实我们的说法，并且证明了我们的算法与适当选择的行为策略下的最新算法相比所产生的解决方案的优越性。

##### URL
[http://arxiv.org/abs/1801.10287](http://arxiv.org/abs/1801.10287)

##### PDF
[http://arxiv.org/pdf/1801.10287](http://arxiv.org/pdf/1801.10287)

