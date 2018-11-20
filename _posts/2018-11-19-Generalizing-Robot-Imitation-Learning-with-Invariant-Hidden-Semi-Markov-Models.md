---
layout: post
title: "Generalizing Robot Imitation Learning with Invariant Hidden Semi-Markov Models"
date: 2018-11-19 04:04:46
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Ajay Kumar Tanwani, Jonathan Lee, Brijen Thananjeyan, Michael Laskey, Sanjay Krishnan, Roy Fox, Ken Goldberg, Sylvain Calinon
mathjax: true
---

* content
{:toc}

##### Abstract
Generalizing manipulation skills to new situations requires extracting invariant patterns from demonstrations. For example, the robot needs to understand the demonstrations at a higher level while being invariant to the appearance of the objects, geometric aspects of objects such as its position, size, orientation and viewpoint of the observer in the demonstrations. In this paper, we propose an algorithm that learns a joint probability density function of the demonstrations with invariant formulations of hidden semi-Markov models to extract invariant segments (also termed as sub-goals or options), and smoothly follow the generated sequence of states with a linear quadratic tracking controller. The algorithm takes as input the demonstrations with respect to different coordinate systems describing virtual landmarks or objects of interest with a task-parameterized formulation, and adapt the segments according to the environmental changes in a systematic manner. We present variants of this algorithm in latent space with low-rank covariance decompositions, semi-tied covariances, and non-parametric online estimation of model parameters under small variance asymptotics; yielding considerably low sample and model complexity for acquiring new manipulation skills. The algorithm allows a Baxter robot to learn a pick-and-place task while avoiding a movable obstacle based on only 4 kinesthetic demonstrations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07489](http://arxiv.org/abs/1811.07489)

##### PDF
[http://arxiv.org/pdf/1811.07489](http://arxiv.org/pdf/1811.07489)

