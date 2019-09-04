---
layout: post
title: "Push for Quantization: Deep Fisher Hashing"
date: 2019-08-31 12:18:43
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Yunqiang Li, Wenjie Pei, Yufei zha, Jan van Gemert
mathjax: true
---

* content
{:toc}

##### Abstract
Current massive datasets demand light-weight access for analysis. Discrete hashing methods are thus beneficial because they map high-dimensional data to compact binary codes that are efficient to store and process, while preserving semantic similarity. To optimize powerful deep learning methods for image hashing, gradient-based methods are required. Binary codes, however, are discrete and thus have no continuous derivatives. Relaxing the problem by solving it in a continuous space and then quantizing the solution is not guaranteed to yield separable binary codes. The quantization needs to be included in the optimization. In this paper we push for quantization: We optimize maximum class separability in the binary space. We introduce a margin on distances between dissimilar image pairs as measured in the binary space. In addition to pair-wise distances, we draw inspiration from Fisher's Linear Discriminant Analysis (Fisher LDA) to maximize the binary distances between classes and at the same time minimize the binary distance of images within the same class. Experiments on CIFAR-10, NUS-WIDE and ImageNet100 demonstrate compact codes comparing favorably to the current state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00206](http://arxiv.org/abs/1909.00206)

##### PDF
[http://arxiv.org/pdf/1909.00206](http://arxiv.org/pdf/1909.00206)

