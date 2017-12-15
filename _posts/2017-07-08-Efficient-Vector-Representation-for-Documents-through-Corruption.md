---
layout: post
title: "Efficient Vector Representation for Documents through Corruption"
date: 2017-07-08 00:57:01
categories: arXiv_CL
tags: arXiv_CL Regularization Sentiment Embedding Represenation_Learning Classification Language_Model
author: Minmin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient document representation learning framework, Document Vector through Corruption (Doc2VecC). Doc2VecC represents each document as a simple average of word embeddings. It ensures a representation generated as such captures the semantic meanings of the document during learning. A corruption model is included, which introduces a data-dependent regularization that favors informative or rare words while forcing the embeddings of common and non-discriminative ones to be close to zero. Doc2VecC produces significantly better word embeddings than Word2Vec. We compare Doc2VecC with several state-of-the-art document representation learning algorithms. The simple model architecture introduced by Doc2VecC matches or out-performs the state-of-the-art in generating high-quality document representations for sentiment analysis, document classification as well as semantic relatedness tasks. The simplicity of the model enables training on billions of words per hour on a single machine. At the same time, the model is very efficient in generating representations of unseen documents at test time.

##### Abstract (translated by Google)
我们提出了一个高效的文档表示学习框架，通过腐败的文档向量（Doc2VecC）。 Doc2VecC将每个文档表示为单词嵌入的简单平均值。它确保生成的表示能够捕获学习期间文档的语义含义。包括一个腐败模型，它引入了依赖数据的正则化，有利于提供信息或罕见的词语，同时迫使常见和不歧视词汇的嵌入接近于零。 Doc2VecC产生比Word2Vec更好的字嵌入。我们比较Doc2VecC和几种最先进的文档表示学习算法。 Doc2VecC引入的简单模型架构匹配或超越了生成高品质文档表示的情境分析，文档分类以及语义相关性任务的最新技术。该模型的简单性使得可以在单台机器上每小时训练数十亿字。同时，该模型在测试时间生成未见文档的表示方面非常高效。

##### URL
[https://arxiv.org/abs/1707.02377](https://arxiv.org/abs/1707.02377)

##### PDF
[https://arxiv.org/pdf/1707.02377](https://arxiv.org/pdf/1707.02377)

