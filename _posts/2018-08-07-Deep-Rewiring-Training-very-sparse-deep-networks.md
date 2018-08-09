---
layout: post
title: "Deep Rewiring: Training very sparse deep networks"
date: 2018-08-07 18:12:10
categories: arXiv_AI
tags: arXiv_AI Sparse RNN Deep_Learning
author: Guillaume Bellec, David Kappel, Wolfgang Maass, Robert Legenstein
mathjax: true
---

* content
{:toc}

##### Abstract
Neuromorphic hardware tends to pose limits on the connectivity of deep networks that one can run on them. But also generic hardware and software implementations of deep learning run more efficiently for sparse networks. Several methods exist for pruning connections of a neural network after it was trained without connectivity constraints. We present an algorithm, DEEP R, that enables us to train directly a sparsely connected neural network. DEEP R automatically rewires the network during supervised training so that connections are there where they are most needed for the task, while its total number is all the time strictly bounded. We demonstrate that DEEP R can be used to train very sparse feedforward and recurrent neural networks on standard benchmark tasks with just a minor loss in performance. DEEP R is based on a rigorous theoretical foundation that views rewiring as stochastic sampling of network configurations from a posterior.

##### Abstract (translated by Google)
神经形态硬件往往会对可以在其上运行的深层网络的连接性造成限制。但是，对于稀疏网络，深度学习的通用硬件和软件实现也更有效。存在几种方法用于在没有连接约束的情况下训练神经网络之后修剪神经网络的连接。我们提出了一种算法DEEP R，它使我们能够直接训练稀疏连接的神经网络。 DEEP R在监督培训期间自动重新连接网络，以便在任务最需要的地方建立连接，而其总数始终严格限制。我们证明DEEP R可用于在标准基准任务上训练非常稀疏的前馈和递归神经网络，而性能损失很小。 DEEP R基于严格的理论基础，将重新布线视为后验网络配置的随机抽样。

##### URL
[http://arxiv.org/abs/1711.05136](http://arxiv.org/abs/1711.05136)

##### PDF
[http://arxiv.org/pdf/1711.05136](http://arxiv.org/pdf/1711.05136)

