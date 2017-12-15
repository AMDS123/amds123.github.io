---
layout: post
title: "Hash Embeddings for Efficient Word Representations"
date: 2017-09-12 16:13:10
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Dan Svenstrup, Jonas Meinertz Hansen, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
We present hash embeddings, an efficient method for representing words in a continuous vector form. A hash embedding may be seen as an interpolation between a standard word embedding and a word embedding created using a random hash function (the hashing trick). In hash embeddings each token is represented by $k$ $d$-dimensional embeddings vectors and one $k$ dimensional weight vector. The final $d$ dimensional representation of the token is the product of the two. Rather than fitting the embedding vectors for each token these are selected by the hashing trick from a shared pool of $B$ embedding vectors. Our experiments show that hash embeddings can easily deal with huge vocabularies consisting of millions of tokens. When using a hash embedding there is no need to create a dictionary before training nor to perform any kind of vocabulary pruning after training. We show that models trained using hash embeddings exhibit at least the same level of performance as models trained using regular embeddings across a wide range of tasks. Furthermore, the number of parameters needed by such an embedding is only a fraction of what is required by a regular embedding. Since standard embeddings and embeddings constructed using the hashing trick are actually just special cases of a hash embedding, hash embeddings can be considered an extension and improvement over the existing regular embedding types.

##### Abstract (translated by Google)
我们提出哈希嵌入，一个有效的方法来表示连续向量形式的单词。散列嵌入可以被看作标准字嵌入和使用随机散列函数（散列技巧）创建的字嵌入之间的插值。在散列嵌入中，每个标记由$ k $ $ d $  - 维嵌入向量和一个$ k $维权向量表示。令牌的最后$ d $维表示是两者的结果。不是为每个标记拟合嵌入向量，而是通过$ B $嵌入向量的共享池中的散列技巧来选择它们。我们的实验表明，哈希嵌入可以很容易地处理由数百万个令牌组成的巨大词汇表。当使用散列嵌入时，不需要在训练之前创建字典，也不需要在训练之后执行任何类型的词汇修剪。我们展示了使用哈希嵌入训练的模型展现出至少与在广泛的任务中使用常规嵌入训练的模型相同的性能水平。此外，这种嵌入所需的参数数量只是常规嵌入所需的参数的一小部分。由于使用散列技巧构造的标准嵌入和嵌入实际上只是散列嵌入的特殊情况，所以散列嵌入可以被认为是对现有常规嵌入类型的扩展和改进。

##### URL
[https://arxiv.org/abs/1709.03933](https://arxiv.org/abs/1709.03933)

##### PDF
[https://arxiv.org/pdf/1709.03933](https://arxiv.org/pdf/1709.03933)

