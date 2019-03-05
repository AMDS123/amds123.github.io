---
layout: post
title: "Learning to Update for Object Tracking with Recurrent Meta-learner"
date: 2019-03-04 15:02:10
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking RNN Gradient_Descent Relation
author: Bi Li, Wenxuan Xie, Wenjun Zeng, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Model update lies at the heart of object tracking. Generally, model update is formulated as an online learning problem where a target model is learned over the online training set. Our key innovation is to \emph{formulate the model update problem in the meta-learning framework and learn the online learning algorithm itself using large numbers of offline videos}, i.e., \emph{learning to update}. The learned updater takes as input the online training set and outputs an updated target model. As a first attempt, we design the learned updater based on recurrent neural networks (RNNs) and demonstrate its application in a template-based tracker and a correlation filter-based tracker. Our learned updater consistently improves the base trackers and runs faster than realtime on GPU while requiring small memory footprint during testing. Experiments on standard benchmarks demonstrate that our learned updater outperforms commonly used update baselines including the efficient exponential moving average (EMA)-based update and the well-designed stochastic gradient descent (SGD)-based update. Equipped with our learned updater, the template-based tracker achieves state-of-the-art performance among realtime trackers on GPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.07078](http://arxiv.org/abs/1806.07078)

##### PDF
[http://arxiv.org/pdf/1806.07078](http://arxiv.org/pdf/1806.07078)

