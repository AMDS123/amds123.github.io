---
layout: post
title: "Progressive Differentiable Architecture Search: Bridging the Depth Gap between Search and Evaluation"
date: 2019-04-29 14:59:28
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Xin Chen, Lingxi Xie, Jun Wu, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, differentiable search methods have made major progress in reducing the computational costs of neural architecture search. However, these approaches often report lower accuracy in evaluating the searched architecture or transferring it to another dataset. This is arguably due to the large gap between the architecture depths in search and evaluation scenarios. In this paper, we present an efficient algorithm which allows the depth of searched architectures to grow gradually during the training procedure. This brings two issues, namely, heavier computational overheads and weaker search stability, which we solve using search space approximation and regularization, respectively. With a significantly reduced search time (~7 hours on a single GPU), our approach achieves state-of-the-art performance on both the proxy dataset (CIFAR10 or CIFAR100) and the target dataset (ImageNet). Code is available at https://github.com/chenxin061/pdarts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12760](http://arxiv.org/abs/1904.12760)

##### PDF
[http://arxiv.org/pdf/1904.12760](http://arxiv.org/pdf/1904.12760)

