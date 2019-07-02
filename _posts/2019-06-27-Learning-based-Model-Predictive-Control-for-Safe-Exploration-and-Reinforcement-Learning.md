---
layout: post
title: "Learning-based Model Predictive Control for Safe Exploration and Reinforcement Learning"
date: 2019-06-27 11:37:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Torsten Koller, Felix Berkenkamp, Matteo Turchetta, Joschka Boedecker, Andreas Krause
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning has been successfully used to solve difficult tasks in complex unknown environments. However, these methods typically do not provide any safety guarantees during the learning process. This is particularly problematic, since reinforcement learning agent actively explore their environment. This prevents their use in safety-critical, real-world applications. In this paper, we present a learning-based model predictive control scheme that provides high-probability safety guarantees throughout the learning process. Based on a reliable statistical model, we construct provably accurate confidence intervals on predicted trajectories. Unlike previous approaches, we allow for input-dependent uncertainties. Based on these reliable predictions, we guarantee that trajectories satisfy safety constraints. Moreover, we use a terminal set constraint to recursively guarantee the existence of safe control actions at every iteration. We evaluate the resulting algorithm to safely explore the dynamics of an inverted pendulum and to solve a reinforcement learning task on a cart-pole system with safety constraints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12189](http://arxiv.org/abs/1906.12189)

##### PDF
[http://arxiv.org/pdf/1906.12189](http://arxiv.org/pdf/1906.12189)

