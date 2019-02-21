---
layout: post
title: "Model-Free Adaptive Optimal Control of Episodic Fixed-Horizon Manufacturing Processes using Reinforcement Learning"
date: 2019-02-20 16:00:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Johannes Dornheim, Norbert Link, Peter Gumbsch
mathjax: true
---

* content
{:toc}

##### Abstract
A self-learning optimal control algorithm for episodic fixed-horizon manufacturing processes with time-discrete control actions is proposed and evaluated on a simulated deep drawing process. The control model is built during consecutive process executions under optimal control via reinforcement learning, using the measured product quality as reward after each process execution. Prior model formulation, which is required by state-of-the-art algorithms from model predictive control and approximate dynamic programming, is therefore obsolete. This avoids several difficulties namely in system identification, accurate modelling, and runtime complexity, that arise when dealing with processes subject to nonlinear dynamics and stochastic influences. Instead of using pre-created process and observation models, value function-based reinforcement learning algorithms build functions of expected future reward, which are used to derive optimal process control decisions. The expectation functions are learned online, by interacting with the process. The proposed algorithm takes stochastic variations of the process conditions into account and is able to cope with partial observability. A Q-learning-based method for adaptive optimal control of partially observable episodic fixed-horizon manufacturing processes is developed and studied. The resulting algorithm is instantiated and evaluated by applying it to a simulated stochastic optimal control problem in metal sheet deep drawing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06646](http://arxiv.org/abs/1809.06646)

##### PDF
[http://arxiv.org/pdf/1809.06646](http://arxiv.org/pdf/1809.06646)

