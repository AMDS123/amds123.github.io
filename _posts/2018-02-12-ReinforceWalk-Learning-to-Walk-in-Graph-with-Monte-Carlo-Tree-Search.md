---
layout: post
title: "ReinforceWalk: Learning to Walk in Graph with Monte Carlo Tree Search"
date: 2018-02-12 23:27:23
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Sparse Knowledge Reinforcement_Learning RNN
author: Yelong Shen, Jianshu Chen, Po-Sen Huang, Yuqing Guo, Jianfeng Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to walk over a graph towards a target node for a given input query and a source node is an important problem in applications such as knowledge graph reasoning. It can be formulated as a reinforcement learning (RL) problem that has a known state transition model, but with partial observability and sparse reward. To overcome these challenges, we develop a graph walking agent called ReinforceWalk, which consists of a deep recurrent neural network (RNN) and a Monte Carlo Tree Search (MCTS). To address partial observability, the RNN encodes the history of observations and map it into the Q-value, the policy and the state value. In order to effectively train the agent from sparse reward, we combine MCTS with the RNN policy to generate trajectories with more positive rewards. From these trajectories, we update the network in an off-policy manner using Q-learning and improves the RNN policy. Our proposed RL algorithm repeatedly applies this policy improvement step to learn the entire model. At testing stage, the MCTS is also combined with the RNN to predict the target node with higher accuracy. Experiment results on several graph-walking benchmarks show that we are able to learn better policies from less number of rollouts compared to other baseline methods, which are mainly based on policy gradient method.

##### Abstract (translated by Google)
学习在给定的输入查询和源节点上遍历一个图的目标节点是知识图推理等应用中的一个重要问题。它可以表示为一个强化学习（RL）问题，它具有已知的状态转移模型，但具有部分可观测性和稀疏的奖励。为了克服这些挑战，我们开发了一种名为ReinforceWalk的图形行走代理，它由深回归神经网络（RNN）和蒙特卡洛树搜索（MCTS）组成。为了解决部分可观测性问题，RNN对观测记录进行编码并将其映射到Q值，策略和状态值中。为了从稀疏奖励中有效地训练代理人，我们将MCTS与RNN策略结合起来，产生更积极的奖励轨迹。根据这些轨迹，我们使用Q-learning以不对外策略的方式更新网络，并改进RNN策略。我们提出的RL算法反复应用这个策略改进步骤来学习整个模型。在测试阶段，MCTS还与RNN结合，以更高的精度预测目标节点。在几个图形行走基准测试中的实验结果表明，与主要基于策略梯度方法的其他基线方法相比，我们能够从较少的展示次数中学习更好的策略。

##### URL
[http://arxiv.org/abs/1802.04394](http://arxiv.org/abs/1802.04394)

##### PDF
[http://arxiv.org/pdf/1802.04394](http://arxiv.org/pdf/1802.04394)

