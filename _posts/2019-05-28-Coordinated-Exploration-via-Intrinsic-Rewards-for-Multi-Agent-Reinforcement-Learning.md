---
layout: post
title: "Coordinated Exploration via Intrinsic Rewards for Multi-Agent Reinforcement Learning"
date: 2019-05-28 23:01:02
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Shariq Iqbal, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse rewards are one of the most important challenges in reinforcement learning. In the single-agent setting, these challenges have been addressed by introducing intrinsic rewards that motivate agents to explore unseen regions of their state spaces. Applying these techniques naively to the multi-agent setting results in individual agents exploring independently, without any coordination among themselves. We argue that learning in cooperative multi-agent settings can be accelerated and improved if agents coordinate with respect to what they have explored. In this paper we propose an approach for learning how to dynamically select between different types of intrinsic rewards which consider not just what an individual agent has explored, but all agents, such that the agents can coordinate their exploration and maximize extrinsic returns. Concretely, we formulate the approach as a hierarchical policy where a high-level controller selects among sets of policies trained on different types of intrinsic rewards and the low-level controllers learn the action policies of all agents under these specific rewards. We demonstrate the effectiveness of the proposed approach in a multi-agent learning domain with sparse rewards.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12127](http://arxiv.org/abs/1905.12127)

##### PDF
[http://arxiv.org/pdf/1905.12127](http://arxiv.org/pdf/1905.12127)

