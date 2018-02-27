---
layout: post
title: "Fully Decentralized Multi-Agent Reinforcement Learning with Networked Agents"
date: 2018-02-23 22:53:32
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kaiqing Zhang, Zhuoran Yang, Han Liu, Tong Zhang, Tamer Ba&#x15f;ar
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of \emph{fully decentralized} multi-agent reinforcement learning (MARL), where the agents are located at the nodes of a time-varying communication network. Specifically, we assume that the reward functions of the agents might correspond to different tasks, and are only known to the corresponding agent. Moreover, each agent makes individual decisions based on both the information observed locally and the messages received from its neighbors over the network. Within this setting, the collective goal of the agents is to maximize the globally averaged return over the network through exchanging information with their neighbors. To this end, we propose two decentralized actor-critic algorithms with function approximation, which are applicable to large-scale MARL problems where both the number of states and the number of agents are massively large. Under the decentralized structure, the actor step is performed individually by each agent with no need to infer the policies of others. For the critic step, we propose a consensus update via communication over the network. Our algorithms are fully incremental and can be implemented in an online fashion. Convergence analyses of the algorithms are provided when the value functions are approximated within the class of linear functions. Extensive simulation results with both linear and nonlinear function approximations are presented to validate the proposed algorithms. Our work appears to be the first study of fully decentralized MARL algorithms for networked agents with function approximation, with provable convergence guarantees.

##### Abstract (translated by Google)
我们考虑多Agent强化学习（MARL）的问题，即代理位于时变通信网络的节点。具体来说，我们假设代理人的奖励功能可能对应不同的任务，并且只有相应的代理人才知道。此外，每个代理都根据本地观察到的信息和通过网络从邻居收到的消息做出个人决策。在这种情况下，代理商的共同目标是通过与邻居交换信息来最大化全球平均的网络回报。为此，我们提出了两种具有函数逼近的分散式演员 - 评论者算法，这些算法适用于状态数量和代理人数量都很大的大规模MARL问题。在分散结构下，行动者步骤由每个行为人单独执行，而不需要推断他人的政策。对于评论阶段，我们提出通过网络通信达成共识更新。我们的算法是完全增量式的，可以通过在线方式实现。当值函数在线性函数类中近似时，提供算法的收敛性分析。为了验证所提出的算法，提出了具有线性和非线性函数近似的广泛仿真结果。我们的工作似乎是首次研究具有函数逼近的网络化代理的完全分散式MARL算法，并具有可证明的收敛保证。

##### URL
[http://arxiv.org/abs/1802.08757](http://arxiv.org/abs/1802.08757)

##### PDF
[http://arxiv.org/pdf/1802.08757](http://arxiv.org/pdf/1802.08757)

