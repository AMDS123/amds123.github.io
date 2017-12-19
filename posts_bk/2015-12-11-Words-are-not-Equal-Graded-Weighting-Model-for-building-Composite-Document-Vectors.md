---
layout: post
title: "Words are not Equal: Graded Weighting Model for building Composite Document Vectors"
date: 2015-12-11 08:44:45
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Sentiment_Classification RNN Classification
author: Pranjal Singh, Amitabha Mukerjee
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of distributional semantics, composing phrases from word vectors remains an important challenge. Several methods have been tried for benchmark tasks such as sentiment classification, including word vector averaging, matrix-vector approaches based on parsing, and on-the-fly learning of paragraph vectors. Most models usually omit stop words from the composition. Instead of such an yes-no decision, we consider several graded schemes where words are weighted according to their discriminatory relevance with respect to its use in the document (e.g., idf). Some of these methods (particularly tf-idf) are seen to result in a significant improvement in performance over prior state of the art. Further, combining such approaches into an ensemble based on alternate classifiers such as the RNN model, results in an 1.6% performance improvement on the standard IMDB movie review dataset, and a 7.01% improvement on Amazon product reviews. Since these are language free models and can be obtained in an unsupervised manner, they are of interest also for under-resourced languages such as Hindi as well and many more languages. We demonstrate the language free aspects by showing a gain of 12% for two review datasets over earlier results, and also release a new larger dataset for future testing (Singh,2015).

##### Abstract (translated by Google)
尽管分布式语义的成功，但从单词向量组成短语仍然是一个重要的挑战。已经尝试了几种基准任务的方法，例如情感分类，包括词向量平均，基于解析的矩阵向量方法和段向量的即时学习。大多数模型通常会忽略组合中的停用词。我们不考虑这样一个“是”或“否”的决定，而是考虑几个分级计划，根据文档在文档中的使用（例如，idf）的歧视性相关性对词进行加权。这些方法中的一些（特别是tf-idf）被认为在性能上比现有技术水平显着改善。此外，将这些方法结合到基于替代分类器（如RNN模型）的集成中，可以使标准IMDB电影评论数据集的性能提高1.6％，对亚马逊产品评论提高7.01％。由于这些都是免费的语言模型，并且可以以无人监督的方式获得，所以它们也对资源不足的语言（例如印地语以及更多的语言）感兴趣。我们通过比较早期结果显示两个评估数据集获得12％的收益来证明语言无关的方面，并且还为未来的测试发布了一个新的更大的数据集（Singh，2015）。

##### URL
[https://arxiv.org/abs/1512.03549](https://arxiv.org/abs/1512.03549)

##### PDF
[https://arxiv.org/pdf/1512.03549](https://arxiv.org/pdf/1512.03549)

