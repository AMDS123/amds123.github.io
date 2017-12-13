---
layout: post
title: "Synonym Discovery with Etymology-based Word Embeddings"
date: 2017-12-12 12:57:59
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Seunghyun Yoon, Pablo Estrada, Kyomin Jung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to learn word embeddings based on an extended version of the distributional hypothesis. Our model derives word embedding vectors using the etymological composition of words, rather than the context in which they appear. It has the strength of not requiring a large text corpus, but instead it requires reliable access to etymological roots of words, making it specially fit for languages with logographic writing systems. The model consists on three steps: (1) building an etymological graph, which is a bipartite network of words and etymological roots, (2) obtaining the biadjacency matrix of the etymological graph and reducing its dimensionality, (3) using columns/rows of the resulting matrices as embedding vectors. We test our model in the Chinese and Sino-Korean vocabularies. Our graphs are formed by a set of 117,000 Chinese words, and a set of 135,000 Sino-Korean words. In both cases we show that our model performs well in the task of synonym discovery.

##### Abstract (translated by Google)
我们提出了一种新的方法来学习基于扩展版本的分布假设的词嵌入。我们的模型使用单词的词源组成来导出单词嵌入向量，而不是它们出现的上下文。它具有不需要大量文本语料库的优势，而是需要可靠地访问词源的词源，使其特别适合于具有文字书写系统的语言。该模型由三个步骤组成：（1）建立一个词源图，这是一个词和词源词根的二分网络，（2）获得词源图的双向性矩阵并降低其维数;（3）使用列/行得到的矩阵作为嵌入向量。我们用汉语和汉语词汇来测试我们的模型。我们的图表是由117,000个中文单词和一套13.5万个中韩单词组成的。在这两种情况下，我们都表明我们的模型在同义词发现任务中表现良好。

##### URL
[http://arxiv.org/abs/1709.10445](http://arxiv.org/abs/1709.10445)

##### PDF
[http://arxiv.org/pdf/1709.10445](http://arxiv.org/pdf/1709.10445)

