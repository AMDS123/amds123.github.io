---
layout: post
title: "Combining Coarse and Fine Physics for Manipulation using Parallel-in-Time Integration"
date: 2019-03-20 12:23:29
categories: arXiv_RO
tags: arXiv_RO Optimization Prediction
author: Wisdom C. Agboh, Daniel Ruprecht, Mehmet R. Dogar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for fast and accurate physics-based predictions during non-prehensile manipulation planning and control. Given an initial state and a sequence of controls, the problem of predicting the resulting sequence of states is a key component of a variety of model-based planning and control algorithms. We propose combining a coarse (i.e. computationally cheap but not very accurate) predictive physics model, with a fine (i.e. computationally expensive but accurate) predictive physics model, to generate a hybrid model that is at the required speed and accuracy for a given manipulation task. Our approach is based on the Parareal algorithm, a parallel-in-time integration method used for computing numerical solutions for general systems of ordinary differential equations. We use Parareal to combine a coarse pushing model with an off-the-shelf physics engine to deliver physics-based predictions that are as accurate as the physics engine but runs in substantially less wall-clock time, thanks to Parareal being amenable to parallelization. We use these physics-based predictions in a model-predictive-control framework based on trajectory optimization, to plan pushing actions that avoid an obstacle and reach a goal location. We show that by combining the two physics models, we can achieve the same success rates as the planner that uses the off-the-shelf physics engine directly, but significantly faster. We present experiments in simulation and on a real robotic setup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08470](http://arxiv.org/abs/1903.08470)

##### PDF
[http://arxiv.org/pdf/1903.08470](http://arxiv.org/pdf/1903.08470)

