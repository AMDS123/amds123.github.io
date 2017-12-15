---
layout: post
title: "Deep API Learning"
date: 2017-07-14 01:22:18
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning Language_Model
author: Xiaodong Gu, Hongyu Zhang, Dongmei Zhang, Sunghun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Developers often wonder how to implement a certain functionality (e.g., how to parse XML files) using APIs. Obtaining an API usage sequence based on an API-related natural language query is very helpful in this regard. Given a query, existing approaches utilize information retrieval models to search for matching API sequences. These approaches treat queries and APIs as bag-of-words (i.e., keyword matching or word-to-word alignment) and lack a deep understanding of the semantics of the query. We propose DeepAPI, a deep learning based approach to generate API usage sequences for a given natural language query. Instead of a bags-of-words assumption, it learns the sequence of words in a query and the sequence of associated APIs. DeepAPI adapts a neural language model named RNN Encoder-Decoder. It encodes a word sequence (user query) into a fixed-length context vector, and generates an API sequence based on the context vector. We also augment the RNN Encoder-Decoder by considering the importance of individual APIs. We empirically evaluate our approach with more than 7 million annotated code snippets collected from GitHub. The results show that our approach generates largely accurate API sequences and outperforms the related approaches.

##### Abstract (translated by Google)
开发人员经常想知道如何使用API​​实现某些功能（例如，如何解析XML文件）。基于API相关的自然语言查询获取API使用序列在这方面是非常有用的。给定查询，现有的方法利用信息检索模型来搜索匹配的API序列。这些方法将查询和API视为词袋（即，关键字匹配或字对词对齐），并且对查询的语义缺乏深入的理解。我们提出DeepAPI，这是一种深度学习的方法，用于为给定的自然语言查询生成API使用序列。学习查询中的单词顺序以及关联的API顺序，而不是一袋一词的假设。 DeepAPI使用名为RNN编码器 - 解码器的神经语言模型。它将单词序列（用户查询）编码成固定长度的上下文向量，并基于该上下文向量生成API序列。我们还通过考虑各个API的重要性来增强RNN编码器 - 解码器。我们通过从GitHub收集的超过700万个带注释的代码片段来经验性地评估我们的方法。结果表明，我们的方法产生很大程度上准确的API序列，并且胜过相关的方法。

##### URL
[https://arxiv.org/abs/1605.08535](https://arxiv.org/abs/1605.08535)

##### PDF
[https://arxiv.org/pdf/1605.08535](https://arxiv.org/pdf/1605.08535)

