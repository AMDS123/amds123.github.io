---
layout: post
title: "Visually Aligned Word Embeddings for Improving Zero-shot Learning"
date: 2017-07-18 01:07:32
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Ruizhi Qiao, Lingqiao Liu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) highly depends on a good semantic embedding to connect the seen and unseen classes. Recently, distributed word embeddings (DWE) pre-trained from large text corpus have become a popular choice to draw such a connection. Compared with human defined attributes, DWEs are more scalable and easier to obtain. However, they are designed to reflect semantic similarity rather than visual similarity and thus using them in ZSL often leads to inferior performance. To overcome this visual-semantic discrepancy, this work proposes an objective function to re-align the distributed word embeddings with visual information by learning a neural network to map it into a new representation called visually aligned word embedding (VAWE). Thus the neighbourhood structure of VAWEs becomes similar to that in the visual domain. Note that in this work we do not design a ZSL method that projects the visual features and semantic embeddings onto a shared space but just impose a requirement on the structure of the mapped word embeddings. This strategy allows the learned VAWE to generalize to various ZSL methods and visual features. As evaluated via four state-of-the-art ZSL methods on four benchmark datasets, the VAWE exhibit consistent performance improvement.

##### Abstract (translated by Google)
零点学习（ZSL）高度依赖于良好的语义嵌入来连接看到和看不见的类。最近，从大型文本语料库中预先训练的分布式词嵌入（DWE）已成为绘制这种连接的流行选择。与人类定义的属性相比，DWE更具可扩展性，更容易获得。然而，它们被设计为反映语义相似性而不是视觉相似性，因此在ZSL中使用它们通常导致较差的性能。为了克服这种视觉语义差异，本文提出了一种目标函数，通过学习神经网络将分布式词嵌入与视觉信息重新对齐，以将其映射到称为视觉对齐词嵌入（VAWE）的新表示中。因此，VAWEs的邻域结构变得与视觉领域中的相似。请注意，在这项工作中，我们没有设计一个将视觉特征和语义嵌入投影到共享空间的ZSL方法，而只是对映射的字嵌入结构施加要求。这个策略允许学习的VAWE推广到各种ZSL方法和视觉特征。通过在四个基准数据集上的四种最先进的ZSL方法进行评估，VAWE展现出一致的性能改进。

##### URL
[https://arxiv.org/abs/1707.05427](https://arxiv.org/abs/1707.05427)

##### PDF
[https://arxiv.org/pdf/1707.05427](https://arxiv.org/pdf/1707.05427)

