---
layout: post
title: "Accelerated Methods for Deep Reinforcement Learning"
date: 2019-01-10 20:48:11
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Adam Stooke, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) has achieved many recent successes, yet experiment turn-around time remains a key bottleneck in research and in practice. We investigate how to optimize existing deep RL algorithms for modern computers, specifically for a combination of CPUs and GPUs. We confirm that both policy gradient and Q-value learning algorithms can be adapted to learn using many parallel simulator instances. We further find it possible to train using batch sizes considerably larger than are standard, without negatively affecting sample complexity or final performance. We leverage these facts to build a unified framework for parallelization that dramatically hastens experiments in both classes of algorithm. All neural network computations use GPUs, accelerating both data collection and training. Our results include using an entire DGX-1 to learn successful strategies in Atari games in mere minutes, using both synchronous and asynchronous algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.02811](http://arxiv.org/abs/1803.02811)

##### PDF
[http://arxiv.org/pdf/1803.02811](http://arxiv.org/pdf/1803.02811)

