---
layout: post
title: "Theory III: Dynamics and Generalization in Deep Networks"
date: 2019-03-12 15:24:26
categories: arXiv_AI
tags: arXiv_AI Review Classification Gradient_Descent
author: Andrzej Banburski, Qianli Liao, Brando Miranda, Lorenzo Rosasco, Bob Liang, Jack Hidary, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
We review recent observations on the dynamical systems induced by gradient descent methods used for training deep networks and summarize properties of the solutions they converge to. Recent results illuminate the absence of overfitting in the special case of linear networks for binary classification. They prove that minimization of loss functions such as the logistic, the cross-entropy and the exponential loss yields asymptotic convergence to the maximum margin solution for linearly separable datasets, independently of the initial conditions. Here we discuss the case of nonlinear DNNs near zero minima of the empirical loss, under exponential-type and square losses, for several variations of the basic gradient descent algorithm, including a new NMGD (norm minimizing gradient descent) version that converges to the minimum norm fixed points of the gradient descent iteration. Our main results are: 1) gradient descent algorithms with weight normalization constraint achieve generalization; 2) the fundamental reason for the effectiveness of existing weight normalization and batch normalization techniques is that they are approximate implementations of maximizing the margin under unit norm constraint; 3) without unit norm constraints some level of generalization can still be obtained for not-too-deep networks because the balance of the weights across different layers, if present at initialization, is maintained by the gradient flow. In the perspective of these theoretical results, we discuss experimental evidence around the apparent absence of overfitting, that is the observation that the expected classification error does not get worse when increasing the number of parameters. Our explanation focuses on the implicit normalization enforced by algorithms such as batch normalization. In particular, the control of the norm of the weights is related to Halpern iterations for minimum norm solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04991](http://arxiv.org/abs/1903.04991)

##### PDF
[http://arxiv.org/pdf/1903.04991](http://arxiv.org/pdf/1903.04991)

