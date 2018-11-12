---
layout: post
title: "Gradient Descent Finds Global Minima of Deep Neural Networks"
date: 2018-11-09 07:39:59
categories: arXiv_AI
tags: arXiv_AI CNN Gradient_Descent
author: Simon S. Du, Jason D. Lee, Haochuan Li, Liwei Wang, Xiyu Zhai
mathjax: true
---

* content
{:toc}

##### Abstract
Gradient descent finds a global minimum in training deep neural networks despite the objective function being non-convex. The current paper proves gradient descent achieves zero training loss in polynomial time for a deep over-parameterized neural network with residual connections (ResNet). Our analysis relies on the particular structure of the Gram matrix induced by the neural network architecture. This structure allows us to show the Gram matrix is stable throughout the training process and this stability implies the global optimality of the gradient descent algorithm. Our bounds also shed light on the advantage of using ResNet over the fully connected feedforward architecture; our bound requires the number of neurons per layer scaling exponentially with depth for feedforward networks whereas for ResNet the bound only requires the number of neurons per layer scaling polynomially with depth. We further extend our analysis to deep residual convolutional neural networks and obtain a similar convergence result.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03804](http://arxiv.org/abs/1811.03804)

##### PDF
[http://arxiv.org/pdf/1811.03804](http://arxiv.org/pdf/1811.03804)

