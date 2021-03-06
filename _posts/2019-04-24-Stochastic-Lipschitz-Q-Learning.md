---
layout: post
title: "Stochastic Lipschitz Q-Learning"
date: 2019-04-24 06:25:42
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Xu Zhu, David Dunson
mathjax: true
---

* content
{:toc}

##### Abstract
In an episodic Markov Decision Process (MDP) problem, an online algorithm chooses from a set of actions in a sequence of $H$ trials, where $H$ is the episode length, in order to maximize the total payoff of the chosen actions. Q-learning, as the most popular model-free reinforcement learning (RL) algorithm, directly parameterizes and updates value functions without explicitly modeling the environment. Recently, [Jin et al. 2018] studies the sample complexity of Q-learning with finite states and actions. Their algorithm achieves nearly optimal regret, which shows that Q-learning can be made sample efficient. However, MDPs with large discrete states and actions [Silver et al. 2016] or continuous spaces [Mnih et al. 2013] cannot learn efficiently in this way. Hence, it is critical to develop new algorithms to solve this dilemma with provable guarantee on the sample complexity. With this motivation, we propose a novel algorithm that works for MDPs with a more general setting, which has infinitely many states and actions and assumes that the payoff function and transition kernel are Lipschitz continuous. We also provide corresponding theory justification for our algorithm. It achieves the regret $\tilde{\mathcal{O}}(K^{\frac{d+1}{d+2}}\sqrt{H^3}),$ where $K$ denotes the number of episodes and $d$ denotes the dimension of the joint space. To the best of our knowledge, this is the first analysis in the model-free setting whose established regret matches the lower bound up to a logarithmic factor.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10653](http://arxiv.org/abs/1904.10653)

##### PDF
[http://arxiv.org/pdf/1904.10653](http://arxiv.org/pdf/1904.10653)

