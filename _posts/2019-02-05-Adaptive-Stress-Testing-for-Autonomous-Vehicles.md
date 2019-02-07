---
layout: post
title: "Adaptive Stress Testing for Autonomous Vehicles"
date: 2019-02-05 21:10:37
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Mark Koren, Saud Alsaif, Ritchie Lee, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for testing the decision making systems of autonomous vehicles. Our approach involves perturbing stochastic elements in the vehicle's environment until the vehicle is involved in a collision. Instead of applying direct Monte Carlo sampling to find collision scenarios, we formulate the problem as a Markov decision process and use reinforcement learning algorithms to find the most likely failure scenarios. This paper presents Monte Carlo Tree Search (MCTS) and Deep Reinforcement Learning (DRL) solutions that can scale to large environments. We show that DRL can find more likely failure scenarios than MCTS with fewer calls to the simulator. A simulation scenario involving a vehicle approaching a crosswalk is used to validate the framework. Our proposed approach is very general and can be easily applied to other scenarios given the appropriate models of the vehicle and the environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01909](http://arxiv.org/abs/1902.01909)

##### PDF
[http://arxiv.org/pdf/1902.01909](http://arxiv.org/pdf/1902.01909)

