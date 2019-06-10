---
layout: post
title: "Combining Parameter Identification and Trajectory Optimization: Real-time Planning for Information Gain"
date: 2019-06-06 18:01:17
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Keenan Albee, Monica Ekal, Rodrigo Ventura, Richard Linares
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic systems often operate with uncertainties in their dynamics, for example, unknown inertial properties. Broadly, there are two approaches for controlling uncertain systems: design robust controllers in spite of uncertainty, or characterize a system before attempting to control it. This paper proposes a middle-ground approach, making trajectory progress while also accounting for gaining information about the system. More specifically, it combines excitation trajectories which are usually intended to optimize information gain for an estimator, with goal-driven trajectory optimization metrics. For this purpose, a measure of information gain is incorporated (using the Fisher Information Matrix) in a real-time planning framework to produce trajectories favorable for estimation. At the same time, the planner receives stable parameter updates from the estimator, enhancing the system model. An implementation of this learn-as-you-go approach utilizing an Unscented Kalman Filter (UKF) and Nonlinear Model Predictive Controller (NMPC) is demonstrated in simulation. Results for cases with and without information gain and online parameter updates in the system model are presented.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02758](http://arxiv.org/abs/1906.02758)

##### PDF
[http://arxiv.org/pdf/1906.02758](http://arxiv.org/pdf/1906.02758)

