---
layout: post
title: "Super-Convergence: Very Fast Training of Neural Networks Using Large Learning Rates"
date: 2018-05-17 17:40:34
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Leslie N. Smith, Nicholay Topin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe a phenomenon, which we named "super-convergence", where neural networks can be trained an order of magnitude faster than with standard training methods. The existence of super-convergence is relevant to understanding why deep networks generalize well. One of the key elements of super-convergence is training with one learning rate cycle and a large maximum learning rate. A primary insight that allows super-convergence training is that large learning rates regularize the training, hence requiring a reduction of all other forms of regularization in order to preserve an optimal regularization balance. We also derive a simplification of the Hessian Free optimization method to compute an estimate of the optimal learning rate. Experiments demonstrate super-convergence for Cifar-10/100, MNIST and Imagenet datasets, and resnet, wide-resnet, densenet, and inception architectures. In addition, we show that super-convergence provides a greater boost in performance relative to standard training when the amount of labeled training data is limited. The architectures and code to replicate the figures in this paper are available at github.com/lnsmith54/super-convergence. See <a href="http://www.fast.ai/2018/04/30/dawnbench-fastai/">this http URL</a> for an application of super-convergence to win the DAWNBench challenge (see https://dawn.cs.stanford.edu/benchmark/).

##### Abstract (translated by Google)
在本文中，我们描述了一种现象，我们将其命名为“超收敛”，其中神经网络可以比标准训练方法训练快一个数量级。超融合的存在与理解深层网络泛化的原因有关。超级融合的关键要素之一是训练有一个学习速率周期和一个大的最大学习速率。允许超收敛训练的主要观点是大的学习率规范训练，因此需要减少所有其他形式的正则化以保持最佳的正则化平衡。我们还推导了Hessian Free优化方法的简化来计算最优学习率的估计。实验证明Cifar-10/100，MNIST和Imagenet数据集以及resnet，wide-resnet，densenet和初始体系结构都具有超收敛性。此外，我们证明，当标记训练数据量有限时，超融合相对于标准训练提供了更大的性能提升。本文中复制数字的体系结构和代码可在github.com/lnsmith54/super-convergence上找到。请参阅<a href="http://www.fast.ai/2018/04/30/dawnbench-fastai/">此http URL </a>获取超融合应用以赢得DAWNBench挑战（请参阅https ：//dawn.cs.stanford.edu/benchmark/）。

##### URL
[http://arxiv.org/abs/1708.07120](http://arxiv.org/abs/1708.07120)

##### PDF
[http://arxiv.org/pdf/1708.07120](http://arxiv.org/pdf/1708.07120)

