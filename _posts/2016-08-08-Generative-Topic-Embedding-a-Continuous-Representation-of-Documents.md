---
layout: post
title: "Generative Topic Embedding: a Continuous Representation of Documents"
date: 2016-08-08 14:49:07
categories: arXiv_CL
tags: arXiv_CL Embedding Inference Classification
author: Shaohua Li, Tat-Seng Chua, Jun Zhu, Chunyan Miao
mathjax: true
---

* content
{:toc}

##### Abstract
Word embedding maps words into a low-dimensional continuous embedding space by exploiting the local word collocation patterns in a small context window. On the other hand, topic modeling maps documents onto a low-dimensional topic space, by utilizing the global word collocation patterns in the same document. These two types of patterns are complementary. In this paper, we propose a generative topic embedding model to combine the two types of patterns. In our model, topics are represented by embedding vectors, and are shared across documents. The probability of each word is influenced by both its local context and its topic. A variational inference method yields the topic embeddings as well as the topic mixing proportions for each document. Jointly they represent the document in a low-dimensional continuous space. In two document classification tasks, our method performs better than eight existing methods, with fewer features. In addition, we illustrate with an example that our method can generate coherent topics even based on only one document.

##### Abstract (translated by Google)
通过在小的上下文窗口中利用本地词语搭配模式，词嵌入将词语映射到低维连续嵌入空间中。另一方面，通过利用同一文档中的全局词汇搭配模式，主题建模将文档映射到低维主题空间。这两种模式是互补的。在本文中，我们提出了一个生成主题嵌入模型来结合这两种模式。在我们的模型中，主题由嵌入向量表示，并在文档之间共享。每个单词的概率都受到当地语境和主题的影响。变分推理方法产生主题嵌入以及每个文档的主题混合比例。它们共同在一个低维的连续空间中代表文件。在两个文档分类任务中，我们的方法比现有的八个方法执行得更好，功能更少。另外，我们用一个例子来说明，即使只有一个文档，我们的方法也能生成连贯的主题。

##### URL
[https://arxiv.org/abs/1606.02979](https://arxiv.org/abs/1606.02979)

##### PDF
[https://arxiv.org/pdf/1606.02979](https://arxiv.org/pdf/1606.02979)

