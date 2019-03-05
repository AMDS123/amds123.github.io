---
layout: post
title: "Large-scale Distributed Second-order Optimization Using Kronecker-factored Approximate Curvature for Deep Convolutional Neural Networks"
date: 2019-03-03 08:45:32
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Kazuki Osawa, Yohei Tsuji, Yuichiro Ueno, Akira Naruse, Rio Yokota, Satoshi Matsuoka
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale distributed training of deep neural networks suffer from the generalization gap caused by the increase in the effective mini-batch size. Previous approaches try to solve this problem by varying the learning rate and batch size over epochs and layers, or some ad hoc modification of the batch normalization. We propose an alternative approach using a second-order optimization method that shows similar generalization capability to first-order methods, but converges faster and can handle larger mini-batches. To test our method on a benchmark where highly optimized first-order methods are available as references, we train ResNet-50 on ImageNet. We converged to 75% Top-1 validation accuracy in 35 epochs for mini-batch sizes under 16,384, and achieved 75% even with a mini-batch size of 131,072, which took 100 epochs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12019](http://arxiv.org/abs/1811.12019)

##### PDF
[http://arxiv.org/pdf/1811.12019](http://arxiv.org/pdf/1811.12019)

