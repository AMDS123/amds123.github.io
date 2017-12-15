---
layout: post
title: "BinaryConnect: Training Deep Neural Networks with binary weights during propagations"
date: 2016-04-18 13:11:45
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Matthieu Courbariaux, Yoshua Bengio, Jean-Pierre David
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNN) have achieved state-of-the-art results in a wide range of tasks, with the best results obtained with large training sets and large models. In the past, GPUs enabled these breakthroughs because of their greater computational speed. In the future, faster computation at both training and test time is likely to be crucial for further progress and for consumer applications on low-power devices. As a result, there is much interest in research and development of dedicated hardware for Deep Learning (DL). Binary weights, i.e., weights which are constrained to only two possible values (e.g. -1 or 1), would bring great benefits to specialized DL hardware by replacing many multiply-accumulate operations by simple accumulations, as multipliers are the most space and power-hungry components of the digital implementation of neural networks. We introduce BinaryConnect, a method which consists in training a DNN with binary weights during the forward and backward propagations, while retaining precision of the stored weights in which gradients are accumulated. Like other dropout schemes, we show that BinaryConnect acts as regularizer and we obtain near state-of-the-art results with BinaryConnect on the permutation-invariant MNIST, CIFAR-10 and SVHN.

##### Abstract (translated by Google)
深度神经网络（DNN）已经在广泛的任务中取得了最先进的成果，用大型训练集和大型模型获得了最好的结果。在过去，GPU由于其更高的计算速度而实现了这些突破。未来，在训练和测试时间更快的计算对于进一步的进步和低功耗设备上的消费应用可能是至关重要的。因此，对于深度学习（DL）的专用硬件的研究和开发有很大的兴趣。二进制权重，即仅限于两个可能值（例如-1或1）的权重，将通过用简单累加代替许多乘法累加运算而给专用DL硬件带来很大益处，因为乘法器是空间和功率最大的，饥饿的神经网络数字实现的组件。我们介绍BinaryConnect，一种方法，包括在向前和向后传播期间用二进制权重训练DNN，同时保持累积梯度的存储权重的精度。像其他退出计划一样，我们展示BinaryConnect充当正规化器，并且使用置换不变MNIST，CIFAR-10和SVHN上的BinaryConnect获得最接近最先进的结果。

##### URL
[https://arxiv.org/abs/1511.00363](https://arxiv.org/abs/1511.00363)

##### PDF
[https://arxiv.org/pdf/1511.00363](https://arxiv.org/pdf/1511.00363)

