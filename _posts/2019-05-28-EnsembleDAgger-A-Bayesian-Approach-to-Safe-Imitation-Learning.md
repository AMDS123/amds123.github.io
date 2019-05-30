---
layout: post
title: "EnsembleDAgger: A Bayesian Approach to Safe Imitation Learning"
date: 2019-05-28 20:47:20
categories: arXiv_AI
tags: arXiv_AI
author: Kunal Menda, Katherine Driggs-Campbell, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
While imitation learning is often used in robotics, the approach frequently suffers from data mismatch and compounding errors. DAgger is an iterative algorithm that addresses these issues by aggregating training data from both the expert and novice policies, but does not consider the impact of safety. We present a probabilistic extension to DAgger, which attempts to quantify the confidence of the novice policy as a proxy for safety. Our method, EnsembleDAgger, approximates a Gaussian Process using an ensemble of neural networks. Using the variance as a measure of confidence, we compute a decision rule that captures how much we doubt the novice, thus determining when it is safe to allow the novice to act. With this approach, we aim to maximize the novice's share of actions, while constraining the probability of failure. We demonstrate improved safety and learning performance compared to other DAgger variants and classic imitation learning on an inverted pendulum and in the MuJoCo HalfCheetah environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08364](http://arxiv.org/abs/1807.08364)

##### PDF
[http://arxiv.org/pdf/1807.08364](http://arxiv.org/pdf/1807.08364)

