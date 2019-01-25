---
layout: post
title: "Efficient Exploration through Bayesian Deep Q-Networks"
date: 2019-01-24 03:26:22
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Kamyar Azizzadenesheli, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Bayesian Deep Q-Networks (BDQN), a Thompson sampling approach for Deep Reinforcement Learning (DRL) in Markov decision processes (MDP). BDQN is an efficient exploration-exploitation algorithm which combines Thompson sampling with deep-Q networks (DQN) and directly incorporates uncertainty over the Q-value in the last layer of the DQN, on the feature representation layer. This allows us to efficiently carry out Thompson sampling through Gaussian sampling and Bayesian Linear Regression (BLR), which has fast closed-form updates. We apply our method to a wide range of Atari games and compare BDQN to a powerful baseline: the double deep Q-network (DDQN). Since BDQN carries out more efficient exploration, it is able to reach higher rewards substantially faster: in less than 5M-+1M interactions for almost half of the games to reach DDQN scores. We also establish theoretical guarantees for the special case when the feature representation is d-dimensional and fixed. We provide the Bayesian regret of posterior sampling RL (PSRL) and frequentist regret of the optimism in the face of uncertainty (OFU) for episodic MDPs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.04412](http://arxiv.org/abs/1802.04412)

##### PDF
[http://arxiv.org/pdf/1802.04412](http://arxiv.org/pdf/1802.04412)

