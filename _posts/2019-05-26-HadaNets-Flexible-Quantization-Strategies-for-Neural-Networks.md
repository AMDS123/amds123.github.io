---
layout: post
title: "HadaNets: Flexible Quantization Strategies for Neural Networks"
date: 2019-05-26 08:17:54
categories: arXiv_CV
tags: arXiv_CV Inference
author: Yash Akhauri
mathjax: true
---

* content
{:toc}

##### Abstract
On-board processing elements on UAVs are currently inadequate for training and inference of Deep Neural Networks. This is largely due to the energy consumption of memory accesses in such a network. HadaNets introduce a flexible train-from-scratch tensor quantization scheme by pairing a full precision tensor to a binary tensor in the form of a Hadamard product. Unlike wider reduced precision neural network models, we preserve the train-time parameter count, thus out-performing XNOR-Nets without a train-time memory penalty. Such training routines could see great utility in semi-supervised online learning tasks. Our method also offers advantages in model compression, as we reduce the model size of ResNet-18 by 7.43 times with respect to a full precision model without utilizing any other compression techniques. We also demonstrate a 'Hadamard Binary Matrix Multiply' kernel, which delivers a 10-fold increase in performance over full precision matrix multiplication with a similarly optimized kernel.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10759](http://arxiv.org/abs/1905.10759)

##### PDF
[http://arxiv.org/pdf/1905.10759](http://arxiv.org/pdf/1905.10759)

