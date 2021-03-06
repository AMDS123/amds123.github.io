---
layout: post
title: "Hierarchical Reinforcement Learning for Zero-shot Generalization with Subtask Dependencies"
date: 2019-05-24 22:10:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Embedding Relation
author: Sungryull Sohn, Junhyuk Oh, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new RL problem where the agent is required to generalize to a previously-unseen environment characterized by a subtask graph which describes a set of subtasks and their dependencies. Unlike existing hierarchical multitask RL approaches that explicitly describe what the agent should do at a high level, our problem only describes properties of subtasks and relationships among them, which requires the agent to perform complex reasoning to find the optimal subtask to execute. To solve this problem, we propose a neural subtask graph solver (NSGS) which encodes the subtask graph using a recursive neural network embedding. To overcome the difficulty of training, we propose a novel non-parametric gradient-based policy, graph reward propagation, to pre-train our NSGS agent and further finetune it through actor-critic method. The experimental results on two 2D visual domains show that our agent can perform complex reasoning to find a near-optimal way of executing the subtask graph and generalize well to the unseen subtask graphs. In addition, we compare our agent with a Monte-Carlo tree search (MCTS) method showing that our method is much more efficient than MCTS, and the performance of NSGS can be further improved by combining it with MCTS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.07665](http://arxiv.org/abs/1807.07665)

##### PDF
[http://arxiv.org/pdf/1807.07665](http://arxiv.org/pdf/1807.07665)

