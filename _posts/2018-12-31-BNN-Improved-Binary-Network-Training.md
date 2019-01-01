---
layout: post
title: "BNN+: Improved Binary Network Training"
date: 2018-12-31 14:07:08
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Sajad Darabi, Mouloud Belbahri, Matthieu Courbariaux, Vahid Partovi Nia
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) are widely used in many applications. However, their deployment on edge devices has been difficult because they are resource hungry. Binary neural networks (BNN) help to alleviate the prohibitive resource requirements of DNN, where both activations and weights are limited to $1$-bit. We propose an improved binary training method (BNN+), by introducing a regularization function that encourages training weights around binary values. In addition to this, to enhance model performance we add trainable scaling factors to our regularization functions. Furthermore, we use an improved approximation of the derivative of the sign activation function in the backward computation. These additions are based on linear operations that are easily implementable into the binary training framework. We show experimental results on CIFAR-10 obtaining an accuracy of $86.7\%$, on AlexNet and $91.3\%$ with VGG network. On ImageNet, our method also outperforms the traditional BNN method and XNOR-net, using AlexNet by a margin of $4\%$ and $2\%$ top-$1$ accuracy respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11800](http://arxiv.org/abs/1812.11800)

##### PDF
[http://arxiv.org/pdf/1812.11800](http://arxiv.org/pdf/1812.11800)

