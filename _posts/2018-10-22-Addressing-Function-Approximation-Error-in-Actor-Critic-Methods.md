---
layout: post
title: "Addressing Function Approximation Error in Actor-Critic Methods"
date: 2018-10-22 17:37:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Scott Fujimoto, Herke van Hoof, David Meger
mathjax: true
---

* content
{:toc}

##### Abstract
In value-based reinforcement learning methods such as deep Q-learning, function approximation errors are known to lead to overestimated value estimates and suboptimal policies. We show that this problem persists in an actor-critic setting and propose novel mechanisms to minimize its effects on both the actor and the critic. Our algorithm builds on Double Q-learning, by taking the minimum value between a pair of critics to limit overestimation. We draw the connection between target networks and overestimation bias, and suggest delaying policy updates to reduce per-update error and further improve performance. We evaluate our method on the suite of OpenAI gym tasks, outperforming the state of the art in every environment tested.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.09477](http://arxiv.org/abs/1802.09477)

##### PDF
[http://arxiv.org/pdf/1802.09477](http://arxiv.org/pdf/1802.09477)

