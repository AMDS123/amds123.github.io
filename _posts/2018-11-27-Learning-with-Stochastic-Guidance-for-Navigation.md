---
layout: post
title: "Learning with Stochastic Guidance for Navigation"
date: 2018-11-27 00:39:19
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Linhai Xie, Yishu Miao, Sen Wang, Phil Blunsom, Zhihua Wang, Changhao Chen, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the sparse rewards and high degree of environment variation, reinforcement learning approaches such as Deep Deterministic Policy Gradient (DDPG) are plagued by issues of high variance when applied in complex real world environments. We present a new framework for overcoming these issues by incorporating a stochastic switch, allowing an agent to choose between high and low variance policies. The stochastic switch can be jointly trained with the original DDPG in the same framework. In this paper, we demonstrate the power of the framework in a navigation task, where the robot can dynamically choose to learn through exploration, or to use the output of a heuristic controller as guidance. Instead of starting from completely random moves, the navigation capability of a robot can be quickly bootstrapped by several simple independent controllers. The experimental results show that with the aid of stochastic guidance we are able to effectively and efficiently train DDPG navigation policies and achieve significantly better performance than state-of-the-art baselines models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10756](http://arxiv.org/abs/1811.10756)

##### PDF
[http://arxiv.org/pdf/1811.10756](http://arxiv.org/pdf/1811.10756)

