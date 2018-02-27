---
layout: post
title: "Addressing Function Approximation Error in Actor-Critic Methods"
date: 2018-02-26 17:54:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Scott Fujimoto, Herke van Hoof, Dave Meger
mathjax: true
---

* content
{:toc}

##### Abstract
In value-based reinforcement learning methods such as deep Q-learning, function approximation errors are known to lead to overestimated value estimates and suboptimal policies. We show that this problem persists in an actor-critic setting and propose novel mechanisms to minimize its effects on both the actor and critic. Our algorithm takes the minimum value between a pair of critics to restrict overestimation and delays policy updates to reduce per-update error. We evaluate our method on the suite of OpenAI gym tasks, outperforming the state of the art in every environment tested.

##### Abstract (translated by Google)
在深度Q学习等基于价值的强化学习方法中，已知函数逼近误差会导致估计值过高和次优策略。我们表明，这个问题在演员评论家环境中依然存在，并提出了新的机制来尽量减少对演员和评论家的影响。我们的算法采用一对评论者之间的最小值来限制高估，并延迟策略更新以减少每更新错误。我们在OpenAI健身房任务套件中评估我们的方法，在每个测试环境中超越最先进的技术。

##### URL
[http://arxiv.org/abs/1802.09477](http://arxiv.org/abs/1802.09477)

##### PDF
[http://arxiv.org/pdf/1802.09477](http://arxiv.org/pdf/1802.09477)

