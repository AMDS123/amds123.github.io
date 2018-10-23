---
layout: post
title: "Algorithmic Framework for Model-based Deep Reinforcement Learning with Theoretical Guarantees"
date: 2018-10-19 21:09:58
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning Optimization
author: Yuping Luo, Huazhe Xu, Yuanzhi Li, Yuandong Tian, Trevor Darrell, Tengyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based reinforcement learning (RL) is considered to be a promising approach to reduce the sample complexity that hinders model-free RL. However, the theoretical understanding of such methods has been rather limited. This paper introduces a novel algorithmic framework for designing and analyzing model-based RL algorithms with theoretical guarantees. We design a meta-algorithm with a theoretical guarantee of monotone improvement to a local maximum of the expected reward. The meta-algorithm iteratively builds a lower bound of the expected reward based on the estimated dynamical model and sample trajectories, and then maximizes the lower bound jointly over the policy and the model. The framework extends the optimism-in-face-of-uncertainty principle to non-linear dynamical models in a way that requires no explicit uncertainty quantification. Instantiating our framework with simplification gives a variant of model-based RL algorithms Stochastic Lower Bounds Optimization (SLBO). Experiments demonstrate that SLBO achieves state-of-the-art performance when only one million or fewer samples are permitted on a range of continuous control benchmark tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.03858](http://arxiv.org/abs/1807.03858)

##### PDF
[http://arxiv.org/pdf/1807.03858](http://arxiv.org/pdf/1807.03858)

