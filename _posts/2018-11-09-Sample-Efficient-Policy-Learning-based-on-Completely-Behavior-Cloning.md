---
layout: post
title: "Sample-Efficient Policy Learning based on Completely Behavior Cloning"
date: 2018-11-09 10:34:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Qiming Zou, Ling Wang, Ke Lu, Yu Li
mathjax: true
---

* content
{:toc}

##### Abstract
Direct policy search is one of the most important algorithm of reinforcement learning. However, learning from scratch needs a large amount of experience data and can be easily prone to poor local optima. In addition to that, a partially trained policy tends to perform dangerous action to agent and environment. In order to overcome these challenges, this paper proposed a policy initialization algorithm called Policy Learning based on Completely Behavior Cloning (PLCBC). PLCBC first transforms the Model Predictive Control (MPC) controller into a piecewise affine (PWA) function using multi-parametric programming, and uses a neural network to express this function. By this way, PLCBC can completely clone the MPC controller without any performance loss, and is totally training-free. The experiments show that this initialization strategy can help agent learn at the high reward state region, and converge faster and better.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03853](http://arxiv.org/abs/1811.03853)

##### PDF
[http://arxiv.org/pdf/1811.03853](http://arxiv.org/pdf/1811.03853)

