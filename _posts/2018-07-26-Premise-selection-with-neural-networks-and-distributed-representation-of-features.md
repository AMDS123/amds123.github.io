---
layout: post
title: "Premise selection with neural networks and distributed representation of features"
date: 2018-07-26 17:54:58
categories: arXiv_AI
tags: arXiv_AI Sparse Embedding Classification
author: Andrzej Stanis&#x142;aw Kucik, Konstantin Korovin
mathjax: true
---

* content
{:toc}

##### Abstract
We present the problem of selecting relevant premises for a proof of a given statement. When stated as a binary classification task for pairs (conjecture, axiom), it can be efficiently solved using artificial neural networks. The key difference between our advance to solve this problem and previous approaches is the use of just functional signatures of premises. To further improve the performance of the model, we use dimensionality reduction technique, to replace long and sparse signature vectors with their compact and dense embedded versions. These are obtained by firstly defining the concept of a context for each functor symbol, and then training a simple neural network to predict the distribution of other functor symbols in the context of this functor. After training the network, the output of its hidden layer is used to construct a lower dimensional embedding of a functional signature (for each premise) with a distributed representation of features. This allows us to use 512-dimensional embeddings for conjecture-axiom pairs, containing enough information about the original statements to reach the accuracy of 76.45% in premise selection task, only with simple two-layer densely connected neural networks.

##### Abstract (translated by Google)
我们提出了选择相关前提的问题，以证明给定的陈述。当被描述为对（猜想，公理）的二元分类任务时，可以使用人工神经网络有效地解决它。我们解决这个问题的方法与以前的方法之间的关键区别在于使用前提的功能性签名。为了进一步提高模型的性能，我们使用降维技术，用紧凑和密集的嵌入式版本替换长和稀疏签名向量。这些是通过首先为每个仿函数符号定义上下文的概念，然后训练一个简单的神经网络来预测该仿函数上下文中其他仿函数符号的分布而获得的。在训练网络之后，其隐藏层的输出用于构造具有特征的分布式表示的功能签名（对于每个前提）的低维嵌入。这允许我们对猜想 - 公理对使用512维嵌入，包含关于原始语句的足够信息，以在前提选择任务中达到76.45％的准确度，仅使用简单的两层密集连接神经网络。

##### URL
[http://arxiv.org/abs/1807.10268](http://arxiv.org/abs/1807.10268)

##### PDF
[http://arxiv.org/pdf/1807.10268](http://arxiv.org/pdf/1807.10268)

