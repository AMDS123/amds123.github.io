---
layout: post
title: "Attention-based Graph Neural Network for Semi-supervised Learning"
date: 2018-03-10 02:01:35
categories: arXiv_AI
tags: arXiv_AI Attention Prediction
author: Kiran K. Thekumparampil, Chong Wang, Sewoong Oh, Li-Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recently popularized graph neural networks achieve the state-of-the-art accuracy on a number of standard benchmark datasets for graph-based semi-supervised learning, improving significantly over existing approaches. These architectures alternate between a propagation layer that aggregates the hidden states of the local neighborhood and a fully-connected layer. Perhaps surprisingly, we show that a linear model, that removes all the intermediate fully-connected layers, is still able to achieve a performance comparable to the state-of-the-art models. This significantly reduces the number of parameters, which is critical for semi-supervised learning where number of labeled examples are small. This in turn allows a room for designing more innovative propagation layers. Based on this insight, we propose a novel graph neural network that removes all the intermediate fully-connected layers, and replaces the propagation layers with attention mechanisms that respect the structure of the graph. The attention mechanism allows us to learn a dynamic and adaptive local summary of the neighborhood to achieve more accurate predictions. In a number of experiments on benchmark citation networks datasets, we demonstrate that our approach outperforms competing methods. By examining the attention weights among neighbors, we show that our model provides some interesting insights on how neighbors influence each other.

##### Abstract (translated by Google)
最近推广的图形神经网络在基于图形的半监督学习的许多标准基准数据集上实现了最新的精确度，与现有方法相比显着改进。这些体系结构在聚集本地邻域的隐藏状态的传播层和完全连接层之间交替。也许令人惊讶的是，我们展示了一个线性模型，去除了所有中间完全连接层，仍然能够实现与最先进的模型相媲美的性能。这显着减少了参数的数量，这对于半监督式学习（其中标记示例的数量很小）是关键的。这反过来又为设计更多创新传播层提供了空间。基于这种见解，我们提出了一种新颖的图形神经网络，它去除了所有中间完全连接的图层，并用关注图形结构的注意机制来代替传播层。关注机制使我们能够学习邻域的动态和自适应局部摘要，以实现更准确的预测。在关于基准引文网络数据集的大量实验中，我们证明了我们的方法优于竞争方法。通过检查邻居之间的关注权重，我们表明我们的模型提供了一些关于邻居如何相互影响的有趣见解。

##### URL
[https://arxiv.org/abs/1803.03735](https://arxiv.org/abs/1803.03735)

##### PDF
[https://arxiv.org/pdf/1803.03735](https://arxiv.org/pdf/1803.03735)

