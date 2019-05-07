---
layout: post
title: "Learning to Control in Metric Space with Optimal Regret"
date: 2019-05-05 01:42:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Lin F. Yang, Chengzhuo Ni, Mengdi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We study online reinforcement learning for finite-horizon deterministic control systems with {\it arbitrary} state and action spaces. Suppose that the transition dynamics and reward function is unknown, but the state and action space is endowed with a metric that characterizes the proximity between different states and actions. We provide a surprisingly simple upper-confidence reinforcement learning algorithm that uses a function approximation oracle to estimate optimistic Q functions from experiences. We show that the regret of the algorithm after $K$ episodes is $O(HL(KH)^{\frac{d-1}{d}}) $ where $L$ is a smoothness parameter, and $d$ is the doubling dimension of the state-action space with respect to the given metric. We also establish a near-matching regret lower bound. The proposed method can be adapted to work for more structured transition systems, including the finite-state case and the case where value functions are linear combinations of features, where the method also achieve the optimal regret.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01576](http://arxiv.org/abs/1905.01576)

##### PDF
[http://arxiv.org/pdf/1905.01576](http://arxiv.org/pdf/1905.01576)

