---
layout: post
title: "Embedded hyper-parameter tuning by Simulated Annealing"
date: 2019-06-04 15:14:36
categories: arXiv_AI
tags: arXiv_AI Image_Classification Optimization Classification Gradient_Descent
author: Matteo Fischetti, Matteo Stringher
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new metaheuristic training scheme that combines Stochastic Gradient Descent (SGD) and Discrete Optimization in an unconventional way. Our idea is to define a discrete neighborhood of the current SGD point containing a number of "potentially good moves" that exploit gradient information, and to search this neighborhood by using a classical metaheuristic scheme borrowed from Discrete Optimization. 
 In the present paper we investigate the use of a simple Simulated Annealing (SA) metaheuristic that accepts/rejects a candidate new solution in the neighborhood with a probability that depends both on the new solution quality and on a parameter (the temperature) which is modified over time to lower the probability of accepting worsening moves. We use this scheme as an automatic way to perform hyper-parameter tuning, hence the title of the paper. A distinctive feature of our scheme is that hyper-parameters are modified within a single SGD execution (and not in an external loop, as customary) and evaluated on the fly on the current minibatch, i.e., their tuning is fully embedded within the SGD algorithm. 
 The use of SA for training is not new, but previous proposals were mainly intended for non-differentiable objective functions for which SGD is not applied due to the lack of gradients. On the contrary, our SA method requires differentiability of (a proxy of) the loss function, and leverages on the availability of a gradient direction to define local moves that have a large probability to improve the current solution. 
 Computational results on image classification (CIFAR-10) are reported, showing that the proposed approach leads to an improvement of the final validation accuracy for modern Deep Neural Networks such as ResNet34 and VGG16.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01504](http://arxiv.org/abs/1906.01504)

##### PDF
[http://arxiv.org/pdf/1906.01504](http://arxiv.org/pdf/1906.01504)

