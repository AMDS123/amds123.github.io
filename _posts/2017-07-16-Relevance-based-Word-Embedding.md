---
layout: post
title: "Relevance-based Word Embedding"
date: 2017-07-16 22:11:57
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Classification Language_Model
author: Hamed Zamani, W. Bruce Croft
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a high-dimensional dense representation for vocabulary terms, also known as a word embedding, has recently attracted much attention in natural language processing and information retrieval tasks. The embedding vectors are typically learned based on term proximity in a large corpus. This means that the objective in well-known word embedding algorithms, e.g., word2vec, is to accurately predict adjacent word(s) for a given word or context. However, this objective is not necessarily equivalent to the goal of many information retrieval (IR) tasks. The primary objective in various IR tasks is to capture relevance instead of term proximity, syntactic, or even semantic similarity. This is the motivation for developing unsupervised relevance-based word embedding models that learn word representations based on query-document relevance information. In this paper, we propose two learning models with different objective functions; one learns a relevance distribution over the vocabulary set for each query, and the other classifies each term as belonging to the relevant or non-relevant class for each query. To train our models, we used over six million unique queries and the top ranked documents retrieved in response to each query, which are assumed to be relevant to the query. We extrinsically evaluate our learned word representation models using two IR tasks: query expansion and query classification. Both query expansion experiments on four TREC collections and query classification experiments on the KDD Cup 2005 dataset suggest that the relevance-based word embedding models significantly outperform state-of-the-art proximity-based embedding models, such as word2vec and GloVe.

##### Abstract (translated by Google)
学习词汇术语的高维密集表示（也称为词嵌入）最近在自然语言处理和信息检索任务中引起了极大的关注。嵌入向量通常基于大语料库中的术语接近度来学习。这意味着众所周知的词嵌入算法（例如word2vec）中的目标是准确地预测给定单词或上下文的相邻单词。但是，这个目标不一定等同于许多信息检索（IR）任务的目标。各种IR任务的主要目标是获取相关性而不是术语接近性，句法性甚至语义相似性。这是开发无监督的基于相关性的词嵌入模型的动机，其基于查询 - 文档相关性信息学习词表示。本文提出了两种具有不同目标函数的学习模型，学习每个查询的词汇集上的相关性分布，另一个将每个词分类为属于每个查询的相关或不相关的类。为了训练我们的模型，我们使用了超过六百万个唯一的查询和响应于每个查询而被检索的排名最高的文档，这些查询被假定为与查询相关。我们使用两个红外任务本质上评估我们学习的单词表示模型：查询扩展和查询分类。在四个TREC集合上的查询扩展实验和在KDD Cup 2005数据集上的查询分类实验都表明，基于相关性的单词嵌入模型显着优于基于邻近度的先进嵌入模型，如word2vec和GloVe。

##### URL
[https://arxiv.org/abs/1705.03556](https://arxiv.org/abs/1705.03556)

##### PDF
[https://arxiv.org/pdf/1705.03556](https://arxiv.org/pdf/1705.03556)

