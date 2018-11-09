---
layout: post
title: "Reward Estimation for Variance Reduction in Deep Reinforcement Learning"
date: 2018-11-07 20:36:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Relation
author: Joshua Romoff, Peter Henderson, Alexandre Pich&#xe9;, Vincent Francois-Lavet, Joelle Pineau
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement Learning (RL) agents require the specification of a reward signal for learning behaviours. However, introduction of corrupt or stochastic rewards can yield high variance in learning. Such corruption may be a direct result of goal misspecification, randomness in the reward signal, or correlation of the reward with external factors that are not known to the agent. Corruption or stochasticity of the reward signal can be especially problematic in robotics, where goal specification can be particularly difficult for complex tasks. While many variance reduction techniques have been studied to improve the robustness of the RL process, handling such stochastic or corrupted reward structures remains difficult. As an alternative for handling this scenario in model-free RL methods, we suggest using an estimator for both rewards and value functions. We demonstrate that this improves performance under corrupted stochastic rewards in both the tabular and non-linear function approximation settings for a variety of noise types and environments. The use of reward estimation is a robust and easy-to-implement improvement for handling corrupted reward signals in model-free RL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.03359](http://arxiv.org/abs/1805.03359)

##### PDF
[http://arxiv.org/pdf/1805.03359](http://arxiv.org/pdf/1805.03359)

