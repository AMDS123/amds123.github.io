---
layout: post
title: "Gossip training for deep learning"
date: 2016-11-29 17:01:31
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning Gradient_Descent
author: Michael Blot, David Picard, Matthieu Cord, Nicolas Thome
mathjax: true
---

* content
{:toc}

##### Abstract
We address the issue of speeding up the training of convolutional networks. Here we study a distributed method adapted to stochastic gradient descent (SGD). The parallel optimization setup uses several threads, each applying individual gradient descents on a local variable. We propose a new way to share information between different threads inspired by gossip algorithms and showing good consensus convergence properties. Our method called GoSGD has the advantage to be fully asynchronous and decentralized. We compared our method to the recent EASGD in \cite{elastic} on CIFAR-10 show encouraging results.

##### Abstract (translated by Google)
我们解决了加快卷积网络训练的问题。在这里，我们研究一种适用于随机梯度下降（SGD）的分布式方法。并行优化设置使用多个线程，每个线程在局部变量上应用单独的渐变下降。我们提出了一种新的方式来分享八卦算法启发的不同线程之间的信息，并表现出良好的共识收敛性。我们称为GoSGD的方法具有完全异步和分散的优点。我们将我们的方法与CIFAR-10中最近的EASGD相比较，显示出令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1611.09726](https://arxiv.org/abs/1611.09726)

##### PDF
[https://arxiv.org/pdf/1611.09726](https://arxiv.org/pdf/1611.09726)

