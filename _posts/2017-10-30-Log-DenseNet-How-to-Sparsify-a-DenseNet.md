---
layout: post
title: "Log-DenseNet: How to Sparsify a DenseNet"
date: 2017-10-30 22:01:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Recognition
author: Hanzhang Hu, Debadeepta Dey, Allison Del Giorno, Martial Hebert, J. Andrew Bagnell
mathjax: true
---

* content
{:toc}

##### Abstract
Skip connections are increasingly utilized by deep neural networks to improve accuracy and cost-efficiency. In particular, the recent DenseNet is efficient in computation and parameters, and achieves state-of-the-art predictions by directly connecting each feature layer to all previous ones. However, DenseNet's extreme connectivity pattern may hinder its scalability to high depths, and in applications like fully convolutional networks, full DenseNet connections are prohibitively expensive. This work first experimentally shows that one key advantage of skip connections is to have short distances among feature layers during backpropagation. Specifically, using a fixed number of skip connections, the connection patterns with shorter backpropagation distance among layers have more accurate predictions. Following this insight, we propose a connection template, Log-DenseNet, which, in comparison to DenseNet, only slightly increases the backpropagation distances among layers from 1 to ($1 + \log_2 L$), but uses only $L\log_2 L$ total connections instead of $O(L^2)$. Hence, Log-DenseNets are easier than DenseNets to implement and to scale. We demonstrate the effectiveness of our design principle by showing better performance than DenseNets on tabula rasa semantic segmentation, and competitive results on visual recognition.

##### Abstract (translated by Google)
跳过的连接越来越多地被深度神经网络利用，以提高准确性和成本效益。特别是，最近的DenseNet在计算和参数上是高效的，并且通过将每个特征层直接连接到所有先前的预测来实现最新的预测。但是，DenseNet的极端连接模式可能会阻碍其高扩展性，而在完全卷积网络等应用中，完整的DenseNet连接成本过高。这项工作首先通过实验表明，跳过连接的一个关键优势是在反向传播期间在特征层之间具有短距离。具体而言，使用固定数量的跳过连接，具有较短的反向传播距离的连接模式具有更准确的预测。根据这个见解，我们提出了一个连接模板Log-DenseNet，与DenseNet相比，它只是稍微增加了从1到（$ 1 + \ log_2 L $）之间的反向传播距离，但是只使用$ L \ log_2 L $总连接数而不是$ O（L ^ 2）$。因此，Log-DenseNets比DenseNets容易实现和扩展。我们展示了我们的设计原则的有效性，表现出比DenseNets更好的表现语义分割和视觉识别上的竞争结果。

##### URL
[https://arxiv.org/abs/1711.00002](https://arxiv.org/abs/1711.00002)

##### PDF
[https://arxiv.org/pdf/1711.00002](https://arxiv.org/pdf/1711.00002)

