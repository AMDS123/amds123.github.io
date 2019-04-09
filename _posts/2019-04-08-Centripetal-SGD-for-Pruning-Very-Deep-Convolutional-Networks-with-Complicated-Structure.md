---
layout: post
title: "Centripetal SGD for Pruning Very Deep Convolutional Networks with Complicated Structure"
date: 2019-04-08 04:48:02
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Xiaohan Ding, Guiguang Ding, Yuchen Guo, Jungong Han
mathjax: true
---

* content
{:toc}

##### Abstract
The redundancy is widely recognized in Convolutional Neural Networks (CNNs), which enables to remove unimportant filters from convolutional layers so as to slim the network with acceptable performance drop. Inspired by the linear and combinational properties of convolution, we seek to make some filters increasingly close and eventually identical for network slimming. To this end, we propose Centripetal SGD (C-SGD), a novel optimization method, which can train several filters to collapse into a single point in the parameter hyperspace. When the training is completed, the removal of the identical filters can trim the network with NO performance loss, thus no finetuning is needed. By doing so, we have partly solved an open problem of constrained filter pruning on CNNs with complicated structure, where some layers must be pruned following others. Our experimental results on CIFAR-10 and ImageNet have justified the effectiveness of C-SGD-based filter pruning. Moreover, we have provided empirical evidences for the assumption that the redundancy in deep neural networks helps the convergence of training by showing that a redundant CNN trained using C-SGD outperforms a normally trained counterpart with the equivalent width.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03837](http://arxiv.org/abs/1904.03837)

##### PDF
[http://arxiv.org/pdf/1904.03837](http://arxiv.org/pdf/1904.03837)

