---
layout: post
title: "Dueling Posterior Sampling for Preference-Based Reinforcement Learning"
date: 2019-08-04 07:51:36
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Ellen R. Novoseller (1), Yanan Sui (2), Yisong Yue (1), Joel W. Burdick (1) ((1) California Institute of Technology, (2) Stanford University)
mathjax: true
---

* content
{:toc}

##### Abstract
In preference-based reinforcement learning (RL), an agent interacts with the environment while receiving preferences instead of absolute feedback. While there is increasing research activity in preference-based RL, the design of formal frameworks that admit tractable theoretical analysis remains an open challenge. Building upon ideas from preference-based bandit learning and posterior sampling in RL, we present Dueling Posterior Sampling (DPS), which employs preference-based posterior sampling to learn both the system dynamics and the underlying utility function that governs the user's preferences. Because preference feedback is provided on trajectories rather than individual state/action pairs, we develop a Bayesian approach to solving the credit assignment problem, translating user preferences to a posterior distribution over state/action reward models. We prove an asymptotic no-regret rate for DPS with a Bayesian logistic regression credit assignment model; to our knowledge, this is the first regret guarantee for preference-based RL. We also discuss possible avenues for extending this proof methodology to analyze other credit assignment models. Finally, we evaluate the approach empirically, showing competitive performance against existing baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01289](http://arxiv.org/abs/1908.01289)

##### PDF
[http://arxiv.org/pdf/1908.01289](http://arxiv.org/pdf/1908.01289)

