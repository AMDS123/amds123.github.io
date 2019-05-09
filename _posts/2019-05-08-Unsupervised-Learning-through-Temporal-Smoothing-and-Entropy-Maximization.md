---
layout: post
title: "Unsupervised Learning through Temporal Smoothing and Entropy Maximization"
date: 2019-05-08 14:37:38
categories: arXiv_CV
tags: arXiv_CV
author: Per Rutquist
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method for machine learning from unlabeled data in the form of a time-series. The mapping that is learned is shown to extract slowly evolving information that would be useful for control applications, while efficiently filtering out unwanted, higher-frequency noise. 
 The method consists of training a feedforward artificial neural network with backpropagation using two opposing objectives. 
 The first of these is to minimize the squared changes in activations between time steps of each unit in the network. This "temporal smoothing" has the effect of correlating inputs that occur close in time with outputs that are close in the L2-norm. 
 The second objective is to maximize the log determinant of the covariance matrix of activations in each layer of the network. This objective ensures that information from each layer is passed through to the next. This second objective acts as a balance to the first, which on its own would result in a network with all input weights equal to zero.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03100](http://arxiv.org/abs/1905.03100)

##### PDF
[http://arxiv.org/pdf/1905.03100](http://arxiv.org/pdf/1905.03100)

