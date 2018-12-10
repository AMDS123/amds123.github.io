---
layout: post
title: "Off-Policy Deep Reinforcement Learning without Exploration"
date: 2018-12-07 04:03:25
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Scott Fujimoto, David Meger, Doina Precup
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning traditionally considers the task of balancing exploration and exploitation. This work examines batch reinforcement learning--the task of maximally exploiting a given batch of off-policy data, without further data collection. We demonstrate that due to errors introduced by extrapolation, standard off-policy deep reinforcement learning algorithms, such as DQN and DDPG, are only capable of learning with data correlated to their current policy, making them ineffective for most off-policy applications. We introduce a novel class of off-policy algorithms, batch-constrained reinforcement learning, which restricts the action space to force the agent towards behaving on-policy with respect to a subset of the given data. We extend this notion to deep reinforcement learning, and to the best of our knowledge, present the first continuous control deep reinforcement learning algorithm which can learn effectively from uncorrelated off-policy data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02900](http://arxiv.org/abs/1812.02900)

##### PDF
[http://arxiv.org/pdf/1812.02900](http://arxiv.org/pdf/1812.02900)

