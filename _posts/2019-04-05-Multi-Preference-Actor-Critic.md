---
layout: post
title: "Multi-Preference Actor Critic"
date: 2019-04-05 21:50:50
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Gradient_Descent
author: Ishan Durugkar, Matthew Hausknecht, Adith Swaminathan, Patrick MacAlpine
mathjax: true
---

* content
{:toc}

##### Abstract
Policy gradient algorithms typically combine discounted future rewards with an estimated value function, to compute the direction and magnitude of parameter updates. However, for most Reinforcement Learning tasks, humans can provide additional insight to constrain the policy learning. We introduce a general method to incorporate multiple different feedback channels into a single policy gradient loss. In our formulation, the Multi-Preference Actor Critic (M-PAC), these different types of feedback are implemented as constraints on the policy. We use a Lagrangian relaxation to satisfy these constraints using gradient descent while learning a policy that maximizes rewards. Experiments in Atari and Pendulum verify that constraints are being respected and can accelerate the learning process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03295](http://arxiv.org/abs/1904.03295)

##### PDF
[http://arxiv.org/pdf/1904.03295](http://arxiv.org/pdf/1904.03295)

