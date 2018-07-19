---
layout: post
title: "Deep Reinforcement Learning for Swarm Systems"
date: 2018-07-17 18:27:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Embedding
author: Maximilian Hüttenrauch, Adrian Šošić, Gerhard Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep reinforcement learning (RL) methods have been applied successfully to multi-agent scenarios. Typically, these methods rely on a concatenation of agent states to represent the information content required for decentralized decision making. However, concatenation scales poorly to swarm systems with a large number of homogeneous agents as it does not exploit the fundamental properties inherent to these systems: (i) the agents in the swarm are interchangeable and (ii) the exact number of agents in the swarm is irrelevant. Therefore, we propose a new state representation for deep multi-agent RL based on mean embeddings of distributions. We treat the agents as samples of a distribution and use the empirical mean embedding as input for a decentralized policy. We define different feature spaces of the mean embedding using histograms, radial basis functions and a neural network learned end-to-end. We evaluate the representation on two well known problems from the swarm literature (rendezvous and pursuit evasion), in a globally and locally observable setup. For the local setup we furthermore introduce simple communication protocols. Of all approaches, the mean embedding representation using neural network features enables the richest information exchange between neighboring agents facilitating the development of more complex collective strategies.

##### Abstract (translated by Google)
最近，深度强化学习（RL）方法已成功应用于多智能体场景。通常，这些方法依赖于代理状态的串联来表示分散决策所需的信息内容。然而，由于没有利用这些系统固有的基本属性，连接对具有大量同类代理的群系统的扩展性很差：（i）群中的代理是可互换的，以及（ii）群中的代理的确切数量是无关紧要的。因此，我们提出了一种基于均值嵌入分布的深度多智能体RL的新状态表示。我们将代理视为分布的样本，并使用经验均值嵌入作为分散策略的输入。我们使用直方图，径向基函数和端到端学习的神经网络定义平均嵌入的不同特征空间。我们在全球和本地可观察的设置中评估群体文献（交会和追踪逃避）中两个众所周知的问题的表示。对于本地设置，我们还引入了简单的通信协议。在所有方法中，使用神经网络特征的平均嵌入表示使得相邻代理之间的最丰富的信息交换促进了更复杂的集体策略的发展。

##### URL
[https://arxiv.org/abs/1807.06613](https://arxiv.org/abs/1807.06613)

##### PDF
[https://arxiv.org/pdf/1807.06613](https://arxiv.org/pdf/1807.06613)

