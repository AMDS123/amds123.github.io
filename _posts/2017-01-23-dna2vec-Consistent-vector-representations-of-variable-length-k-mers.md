---
layout: post
title: "dna2vec: Consistent vector representations of variable-length k-mers"
date: 2017-01-23 07:21:43
categories: arXiv_SD
tags: arXiv_SD Embedding Language_Model Relation
author: Patrick Ng
mathjax: true
---

* content
{:toc}

##### Abstract
One of the ubiquitous representation of long DNA sequence is dividing it into shorter k-mer components. Unfortunately, the straightforward vector encoding of k-mer as a one-hot vector is vulnerable to the curse of dimensionality. Worse yet, the distance between any pair of one-hot vectors is equidistant. This is particularly problematic when applying the latest machine learning algorithms to solve problems in biological sequence analysis. In this paper, we propose a novel method to train distributed representations of variable-length k-mers. Our method is based on the popular word embedding model word2vec, which is trained on a shallow two-layer neural network. Our experiments provide evidence that the summing of dna2vec vectors is akin to nucleotides concatenation. We also demonstrate that there is correlation between Needleman-Wunsch similarity score and cosine similarity of dna2vec vectors.

##### Abstract (translated by Google)
长DNA序列的普遍表现之一是将其分为较短的k-mer组分。不幸的是，将k-mer作为一个单独的向量进行简单的向量编码容易受到维度的诅咒。更糟的是，任何一对单向矢量之间的距离是等距的。当应用最新的机器学习算法来解决生物序列分析中的问题时，这是特别有问题的。在本文中，我们提出了一种新的方法来训练变长K聚体的分布式表示。我们的方法是基于流行的词嵌入模型word2vec，它在浅层的两层神经网络上训练。我们的实验提供的证据表明dna2vec载体的总结类似于核苷酸连接。我们还证明Needleman-Wunsch相似性分数与dna2vec向量的余弦相似性之间存在相关性。

##### URL
[https://arxiv.org/abs/1701.06279](https://arxiv.org/abs/1701.06279)

##### PDF
[https://arxiv.org/pdf/1701.06279](https://arxiv.org/pdf/1701.06279)

