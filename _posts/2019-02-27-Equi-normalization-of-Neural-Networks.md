---
layout: post
title: "Equi-normalization of Neural Networks"
date: 2019-02-27 09:52:43
categories: arXiv_CV
tags: arXiv_CV
author: Pierre Stock, Benjamin Graham, R&#xe9;mi Gribonval, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural networks are over-parametrized. In particular, each rectified linear hidden unit can be modified by a multiplicative factor by adjusting input and output weights, without changing the rest of the network. Inspired by the Sinkhorn-Knopp algorithm, we introduce a fast iterative method for minimizing the L2 norm of the weights, equivalently the weight decay regularizer. It provably converges to a unique solution. Interleaving our algorithm with SGD during training improves the test accuracy. For small batches, our approach offers an alternative to batch-and group-normalization on CIFAR-10 and ImageNet with a ResNet-18.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10416](http://arxiv.org/abs/1902.10416)

##### PDF
[http://arxiv.org/pdf/1902.10416](http://arxiv.org/pdf/1902.10416)

