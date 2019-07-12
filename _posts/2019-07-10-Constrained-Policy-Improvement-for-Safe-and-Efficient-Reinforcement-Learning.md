---
layout: post
title: "Constrained Policy Improvement for Safe and Efficient Reinforcement Learning"
date: 2019-07-10 20:12:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Elad Sarafian, Aviv Tamar, Sarit Kraus
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a policy improvement algorithm for Reinforcement Learning (RL) which is called Rerouted Behavior Improvement (RBI). RBI is designed to take into account the evaluation errors of the Q-function. Such errors are common in RL when learning the $Q$-value from finite past experience data. Greedy policies or even constrained policy optimization algorithms which ignore these errors may suffer from an improvement penalty (i.e. a negative policy improvement). To minimize the improvement penalty, the RBI idea is to attenuate rapid policy changes of low probability actions which were less frequently sampled. This approach is shown to avoid catastrophic performance degradation and reduce regret when learning from a batch of past experience. Through a two-armed bandit with Gaussian distributed rewards example, we show that it also increases data efficiency when the optimal action has a high variance. We evaluate RBI in two tasks in the Atari Learning Environment: (1) learning from observations of multiple behavior policies and (2) iterative RL. Our results demonstrate the advantage of RBI over greedy policies and other constrained policy optimization algorithms as a safe learning approach and as a general data efficient learning algorithm. An anonymous Github repository of our RBI implementation is found at https://github.com/eladsar/rbi.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07805](http://arxiv.org/abs/1805.07805)

##### PDF
[http://arxiv.org/pdf/1805.07805](http://arxiv.org/pdf/1805.07805)

