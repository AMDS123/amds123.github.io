---
layout: post
title: "Deep Rewiring: Training very sparse deep networks"
date: 2018-02-02 15:57:44
categories: arXiv_AI
tags: arXiv_AI Sparse RNN Deep_Learning
author: Guillaume Bellec, David Kappel, Wolfgang Maass, Robert Legenstein
mathjax: true
---

* content
{:toc}

##### Abstract
Neuromorphic hardware tends to pose limits on the connectivity of deep networks that one can run on them. But also generic hardware and software implementations of deep learning run more efficiently on sparse networks. Several methods exist for pruning connections of a neural network after it was trained without connectivity constraints. We present an algorithm, DEEP R, that enables us to train directly a sparsely connected neural network. DEEP R automatically rewires the network during supervised training so that connections are there where they are most needed for the task, while its total number is all the time strictly bounded. We demonstrate that DEEP R can be used to train very sparse feedforward and recurrent neural networks on standard benchmark tasks with just a minor loss in performance. DEEP R is based on a rigorous theoretical foundation that views rewiring as stochastic sampling of network configurations from a posterior.

##### Abstract (translated by Google)
神经形态硬件往往会对可以在其上运行的深层网络的连接性造成限制。但是，通用的深度学习软硬件实现在稀疏网络上运行效率更高。在训练没有连通性约束的情况下，存在几种用于修剪神经网络的连接的方法。我们提出一个算法，DEEP R，使我们能够直接训练一个稀疏连接的神经网络。 DEEP R在监督训练期间自动重新连接网络，以便连接在那里他们最需要的任务，而其总数是严格限制的。我们证明DEEP R可以用来在标准的基准测试任务上训练非常稀疏的前馈和递归神经网络，只是性能稍有下降。 DEEP R基于一个严格的理论基础，将重新布线视为网络配置的后验抽样。

##### URL
[http://arxiv.org/abs/1711.05136](http://arxiv.org/abs/1711.05136)

##### PDF
[http://arxiv.org/pdf/1711.05136](http://arxiv.org/pdf/1711.05136)

