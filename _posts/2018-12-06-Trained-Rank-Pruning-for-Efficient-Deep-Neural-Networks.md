---
layout: post
title: "Trained Rank Pruning for Efficient Deep Neural Networks"
date: 2018-12-06 08:37:54
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction Gradient_Descent
author: Yuhui Xu, Yuxi Li, Shuai Zhang, Wei Wen, Botao Wang, Yingyong Qi, Yiran Chen, Weiyao Lin, Hongkai Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of Deep Neural Networks (DNNs) keeps elevating in recent years with increasing network depth and width. To enable DNNs on edge devices like mobile phones, researchers proposed several network compression methods including pruning, quantization and factorization. Among the factorization-based approaches, low-rank approximation has been widely adopted because of its solid theoretical rationale and efficient implementations. Several previous works attempted to directly approximate a pre-trained model by low-rank decomposition; however, small approximation errors in parameters can ripple a large prediction loss. As a result, performance usually drops significantly and a sophisticated fine-tuning is required to recover accuracy. We argue that it is not optimal to separate low-rank approximation from training. Unlike previous works, this paper integrates low rank approximation and regularization into the training. We propose Trained Rank Pruning (TRP), which iterates low rank approximation and training. TRP maintains the capacity of original network while imposes low-rank constraints during training. A stochastic sub-gradient descent optimized nuclear regularization is utilized to further encourage low rank in TRP. The TRP trained network has low-rank structure in nature, and can be approximated with negligible performance loss, eliminating fine-tuning after low rank approximation. The methods are comprehensively evaluated on CIFAR-10 and ImageNet, outperforming previous compression methods using low rank approximation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02402](http://arxiv.org/abs/1812.02402)

##### PDF
[http://arxiv.org/pdf/1812.02402](http://arxiv.org/pdf/1812.02402)

