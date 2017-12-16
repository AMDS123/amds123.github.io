---
layout: post
title: "Large Batch Training of Convolutional Networks"
date: 2017-09-13 23:25:07
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Gradient_Descent
author: Yang You, Igor Gitman, Boris Ginsburg
mathjax: true
---

* content
{:toc}

##### Abstract
A common way to speed up training of large convolutional networks is to add computational units. Training is then performed using data-parallel synchronous Stochastic Gradient Descent (SGD) with mini-batch divided between computational units. With an increase in the number of nodes, the batch size grows. But training with large batch size often results in the lower model accuracy. We argue that the current recipe for large batch training (linear learning rate scaling with warm-up) is not general enough and training may diverge. To overcome this optimization difficulties we propose a new training algorithm based on Layer-wise Adaptive Rate Scaling (LARS). Using LARS, we scaled Alexnet up to a batch size of 8K, and Resnet-50 to a batch size of 32K without loss in accuracy.

##### Abstract (translated by Google)
加快大型卷积网络训练的常用方法是增加计算单位。然后使用数据平行同步随机梯度下降（SGD），在计算单位之间进行小批量的训练。随着节点数量的增加，批量增长。但是，大批量训练通常会导致模型精确度降低。我们认为目前大批量训练（线性学习速率缩放与预热）的方法不够普遍，训练可能会有分歧。为了克服这个优化难题，我们提出了一种基于层次自适应速率缩放（LARS）的新型训练算法。使用LARS，我们将Alexnet的批量大小调整为8K，Resnet-50的批量大小为32K，而不会降低准确性。

##### URL
[https://arxiv.org/abs/1708.03888](https://arxiv.org/abs/1708.03888)

##### PDF
[https://arxiv.org/pdf/1708.03888](https://arxiv.org/pdf/1708.03888)

