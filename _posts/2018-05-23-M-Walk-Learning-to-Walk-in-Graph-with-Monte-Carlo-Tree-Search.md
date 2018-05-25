---
layout: post
title: "M-Walk: Learning to Walk in Graph with Monte Carlo Tree Search"
date: 2018-05-23 21:02:01
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning RNN
author: Yelong Shen, Jianshu Chen, Po-Sen Huang, Yuqing Guo, Jianfeng Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to walk over a graph towards a target node for a given input query and a source node is an important problem in applications such as knowledge base completion (KBC). It can be formulated as a reinforcement learning (RL) problem with a known state transition model. To overcome the challenge of sparse reward, we develop a graph-walking agent called M-Walk, which consists of a deep recurrent neural network (RNN) and Monte Carlo Tree Search (MCTS). The RNN encodes the state (i.e., history of the walked path) and maps it separately to a policy, a state value and state-action Q-values. In order to effectively train the agent from sparse reward, we combine MCTS with the neural policy to generate trajectories yielding more positive rewards. From these trajectories, the network is improved in an off-policy manner using Q-learning, which modifies the RNN policy via parameter sharing. Our proposed RL algorithm repeatedly applies this policy-improvement step to learn the entire model. At test time, MCTS is again combined with the neural policy to predict the target node. Experimental results on several graph-walking benchmarks show that M-Walk is able to learn better policies than other RL-based methods, which are mainly based on policy gradients. M-Walk also outperforms traditional KBC baselines.

##### Abstract (translated by Google)
在知识库完成（KBC）等应用程序中，学习如何在给定输入查询和源节点上遍历图形朝向目标节点是一个重要问题。它可以用已知的状态转移模型表示为强化学习（RL）问题。为了克服稀疏奖励的挑战，我们开发了一种称为M-Walk的图形行走代理，它由深回归神经网络（RNN）和蒙特卡罗树搜索（MCTS）组成。 RNN编码状态（即走路的历史）并将其分别映射到策略，状态值和状态动作Q值。为了从稀疏奖励中有效地训练代理人，我们将MCTS与神经策略相结合，以产生更多积极奖励的轨迹。从这些轨迹来看，网络通过使用Q学习在关闭策略方式下得到改进，该学习通过参数共享修改了RNN策略。我们提出的RL算法反复应用此策略改进步骤来学习整个模型。在测试时间，MCTS再次与神经策略相结合来预测目标节点。在几个图形步行基准测试的实验结果表明，M-Walk能够学习比其他基于RL的方法更好的策略，这些方法主要基于策略梯度。 M-Walk也胜过传统的KBC基线。

##### URL
[http://arxiv.org/abs/1802.04394](http://arxiv.org/abs/1802.04394)

##### PDF
[http://arxiv.org/pdf/1802.04394](http://arxiv.org/pdf/1802.04394)

