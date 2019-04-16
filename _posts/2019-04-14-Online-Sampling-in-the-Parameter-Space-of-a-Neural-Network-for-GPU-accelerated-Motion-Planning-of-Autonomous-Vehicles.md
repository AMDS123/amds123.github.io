---
layout: post
title: "Online Sampling in the Parameter Space of a Neural Network for GPU-accelerated Motion Planning of Autonomous Vehicles"
date: 2019-04-14 11:30:58
categories: arXiv_RO
tags: arXiv_RO Tracking Prediction
author: Mogens Graf Plessen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes online sampling in the parameter space of a neural network for GPU-accelerated motion planning of autonomous vehicles. Neural networks are used as controller parametrization since they can handle nonlinear non-convex systems and their complexity does not scale with prediction horizon length. Network parametrizations are sampled at each sampling time and then held constant throughout the prediction horizon. Controls still vary over the prediction horizon due to varying feature vectors fed to the network. Full-dimensional vehicles are modeled by polytopes. Under the assumption of obstacle point data, and their extrapolation over a prediction horizon under constant velocity assumption, collision avoidance reduces to linear inequality checks. Steering and longitudinal acceleration controls are determined simultaneously. The proposed method is designed for parallelization and therefore well-suited to benefit from continuing advancements in hardware such as GPUs. Characteristics of proposed method are illustrated in 5 numerical simulation experiments including dynamic obstacle avoidance, waypoint tracking requiring alternating forward and reverse driving with maximal steering, and a reverse parking scenario.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06680](http://arxiv.org/abs/1904.06680)

##### PDF
[http://arxiv.org/pdf/1904.06680](http://arxiv.org/pdf/1904.06680)

