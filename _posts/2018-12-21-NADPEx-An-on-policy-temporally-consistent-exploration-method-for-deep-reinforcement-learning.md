---
layout: post
title: "NADPEx: An on-policy temporally consistent exploration method for deep reinforcement learning"
date: 2018-12-21 10:17:29
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Sirui Xie, Junning Huang, Lanxin Lei, Chunxiao Liu, Zheng Ma, Wei Zhang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning agents need exploratory behaviors to escape from local optima. These behaviors may include both immediate dithering perturbation and temporally consistent exploration. To achieve these, a stochastic policy model that is inherently consistent through a period of time is in desire, especially for tasks with either sparse rewards or long term information. In this work, we introduce a novel on-policy temporally consistent exploration strategy - Neural Adaptive Dropout Policy Exploration (NADPEx) - for deep reinforcement learning agents. Modeled as a global random variable for conditional distribution, dropout is incorporated to reinforcement learning policies, equipping them with inherent temporal consistency, even when the reward signals are sparse. Two factors, gradients' alignment with the objective and KL constraint in policy space, are discussed to guarantee NADPEx policy's stable improvement. Our experiments demonstrate that NADPEx solves tasks with sparse reward while naive exploration and parameter noise fail. It yields as well or even faster convergence in the standard mujoco benchmark for continuous control.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09028](http://arxiv.org/abs/1812.09028)

##### PDF
[http://arxiv.org/pdf/1812.09028](http://arxiv.org/pdf/1812.09028)

