---
layout: post
title: "Variations on the Chebyshev-Lagrange Activation Function"
date: 2019-06-24 16:38:22
categories: arXiv_AI
tags: arXiv_AI Classification
author: Yuchen Li, Frank Rudzicz, Jekaterina Novikova
mathjax: true
---

* content
{:toc}

##### Abstract
We seek to improve the data efficiency of neural networks and present novel implementations of parameterized piece-wise polynomial activation functions. The parameters are the y-coordinates of n+1 Chebyshev nodes per hidden unit and Lagrangian interpolation between the nodes produces the polynomial on [-1, 1]. We show results for different methods of handling inputs outside [-1, 1] on synthetic datasets, finding significant improvements in capacity of expression and accuracy of interpolation in models that compute some form of linear extrapolation from either ends. We demonstrate competitive or state-of-the-art performance on the classification of images (MNIST and CIFAR-10) and minimally-correlated vectors (DementiaBank) when we replace ReLU or tanh with linearly extrapolated Chebyshev-Lagrange activations in deep residual architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10064](http://arxiv.org/abs/1906.10064)

##### PDF
[http://arxiv.org/pdf/1906.10064](http://arxiv.org/pdf/1906.10064)

