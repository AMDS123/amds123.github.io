---
layout: post
title: "NeST: A Neural Network Synthesis Tool Based on a Grow-and-Prune Paradigm"
date: 2017-11-20 18:45:01
categories: arXiv_CV
tags: arXiv_CV
author: Xiaoliang Dai, Hongxu Yin, Niraj K. Jha
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks (NNs) have begun to have a pervasive impact on various applications of machine learning. However, the problem of finding an optimal NN architecture for large applications has remained open for several decades. Conventional approaches search for the optimal NN architecture through extensive trial-and-error. Such a procedure is quite inefficient. In addition, the generated NN architectures incur substantial redundancy. To address these problems, we propose an NN synthesis tool (NeST) that automatically generates very compact architectures for a given dataset. NeST starts with a seed NN architecture. It iteratively tunes the architecture with gradient-based growth and magnitude-based pruning of neurons and connections. Our experimental results show that NeST yields accurate yet very compact NNs with a wide range of seed architecture selection. For example, for the LeNet-300-100 (LeNet-5) NN architecture derived from the MNIST dataset, we reduce network parameters by 34.1x (74.3x) and floating-point operations (FLOPs) by 35.8x (43.7x). For the AlexNet NN architecture derived from the ImageNet dataset, we reduce network parameters by 15.7x and FLOPs by 4.6x. All these results are the current state-of-the-art for these architectures.

##### Abstract (translated by Google)
神经网络（NN）已经开始对机器学习的各种应用产生广泛的影响。然而，为大型应用寻找最佳NN架构的问题几十年来一直保持开放。传统的方法通过大量的试错来寻找最佳的NN架构。这样的程序相当低效。另外，生成的NN架构会产生相当大的冗余。为了解决这些问题，我们提出了一个NN综合工具（NeST），它可以为给定的数据集自动生成非常紧凑的体系结构。 NeST从种子NN架构开始。它通过基于梯度的增长和基于量值的神经元和连接的修剪迭代地调整架构。我们的实验结果表明，NeST产生精确但非常紧凑的神经网络，具有广泛的种子架构选择。例如，对于从MNIST数据集派生的LeNet-300-100（LeNet-5）NN架构，我们将网络参数减少了34.1倍（74.3倍）和浮点运算（FLOP）35.8倍（43.7倍）。对于从ImageNet数据集派生的AlexNet NN架构，我们将网络参数减少了15.7倍，FLOP减少了4.6倍。所有这些结果都是目前这些架构的最新技术。

##### URL
[https://arxiv.org/abs/1711.02017](https://arxiv.org/abs/1711.02017)

##### PDF
[https://arxiv.org/pdf/1711.02017](https://arxiv.org/pdf/1711.02017)

