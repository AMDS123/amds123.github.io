---
layout: post
title: "Multitask Reinforcement Learning for Zero-shot Generalization with Subtask Dependencies"
date: 2018-07-19 23:51:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Relation
author: Sungryull Sohn, Junhyuk Oh, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new RL problem where the agent is required to execute a given subtask graph which describes a set of subtasks and their dependency. Unlike existing multitask RL approaches that explicitly describe what the agent should do, a subtask graph in our problem only describes properties of subtasks and relationships among them, which requires the agent to perform complex reasoning to find the optimal sequence of subtasks to execute. To tackle this problem, we propose a neural subtask graph solver (NSS) which encodes the subtask graph using a recursive neural network. To overcome the difficulty of training, we propose a novel non-parametric gradient-based policy to pre-train our NSS agent. % and further finetune it through actor-critic method. The experimental results on two 2D visual domains show that our agent can perform complex reasoning to find a near-optimal way of executing the subtask graph and generalize well to the unseen subtask graphs. In addition, we compare our agent with a Monte-Carlo tree search (MCTS) method showing that (1) our method is much more efficient than MCTS and (2) combining MCTS with NSS dramatically improves the search performance.

##### Abstract (translated by Google)
我们引入了一个新的RL问题，其中代理需要执行给定的子任务图，该子图描述了一组子任务及其依赖关系。与明确描述代理应该做什么的现有多任务RL方法不同，我们的问题中的子任务图仅描述子任务的属性和它们之间的关系，这要求代理执行复杂的推理以找到要执行的子任务的最佳序列。为了解决这个问题，我们提出了一种神经子任务图解算器（NSS），它使用递归神经网络对子任务图进行编码。为了克服训练的难度，我们提出了一种新的非参数梯度策略来预训我们的NSS代理。 ％并通过演员评论方法进一步微调它。两个2D视觉域的实验结果表明，我们的代理可以执行复杂的推理，找到执行子任务图的近似最佳方式，并很好地推广到看不见的子任务图。此外，我们将我们的代理与蒙特卡罗树搜索（MCTS）方法进行比较，表明（1）我们的方法比MCTS更有效，（2）MCTS与NSS的结合显着提高了搜索性能。

##### URL
[https://arxiv.org/abs/1807.07665](https://arxiv.org/abs/1807.07665)

##### PDF
[https://arxiv.org/pdf/1807.07665](https://arxiv.org/pdf/1807.07665)

