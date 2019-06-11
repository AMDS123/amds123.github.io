---
layout: post
title: "Discrete Sequential Prediction of Continuous Actions for Deep RL"
date: 2019-06-08 00:56:16
categories: arXiv_AI
tags: arXiv_AI Optimization Prediction
author: Luke Metz, Julian Ibarz, Navdeep Jaitly, James Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
It has long been assumed that high dimensional continuous control problems cannot be solved effectively by discretizing individual dimensions of the action space due to the exponentially large number of bins over which policies would have to be learned. In this paper, we draw inspiration from the recent success of sequence-to-sequence models for structured prediction problems to develop policies over discretized spaces. Central to this method is the realization that complex functions over high dimensional spaces can be modeled by neural networks that predict one dimension at a time. Specifically, we show how Q-values and policies over continuous spaces can be modeled using a next step prediction model over discretized dimensions. With this parameterization, it is possible to both leverage the compositional structure of action spaces during learning, as well as compute maxima over action spaces (approximately). On a simple example task we demonstrate empirically that our method can perform global search, which effectively gets around the local optimization issues that plague DDPG. We apply the technique to off-policy (Q-learning) methods and show that our method can achieve the state-of-the-art for off-policy methods on several continuous control tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.05035](http://arxiv.org/abs/1705.05035)

##### PDF
[http://arxiv.org/pdf/1705.05035](http://arxiv.org/pdf/1705.05035)

