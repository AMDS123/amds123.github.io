---
layout: post
title: "Bayesian Optimization in Variational Latent Spaces with Dynamic Compression"
date: 2019-07-10 15:34:06
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Rika Antonova, Akshara Rai, Tianyu Li, Danica Kragic
mathjax: true
---

* content
{:toc}

##### Abstract
Data-efficiency is crucial for autonomous robots to adapt to new tasks and environments. In this work we focus on robotics problems with a budget of only 10-20 trials. This is a very challenging setting even for data-efficient approaches like Bayesian optimization (BO), especially when optimizing higher-dimensional controllers. Simulated trajectories can be used to construct informed kernels for BO. However, previous work employed supervised ways of extracting low-dimensional features for these. We propose a model and architecture for a sequential variational autoencoder that embeds the space of simulated trajectories into a lower-dimensional space of latent paths in an unsupervised way. We further compress the search space for BO by reducing exploration in parts of the state space that are undesirable, without requiring explicit constraints on controller parameters. We validate our approach with hardware experiments on a Daisy hexapod robot and an ABB Yumi manipulator. We also present simulation experiments with further comparisons to several baselines on Daisy and two manipulators. Our experiments indicate the proposed trajectory-based kernel with dynamic compression can offer ultra data-efficient optimization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04796](http://arxiv.org/abs/1907.04796)

##### PDF
[http://arxiv.org/pdf/1907.04796](http://arxiv.org/pdf/1907.04796)

