---
layout: post
title: "Jointly Learning Word Embeddings and Latent Topics"
date: 2017-06-21 06:19:24
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Bei Shi, Wai Lam, Shoaib Jameel, Steven Schockaert, Kwun Ping Lai
mathjax: true
---

* content
{:toc}

##### Abstract
Word embedding models such as Skip-gram learn a vector-space representation for each word, based on the local word collocation patterns that are observed in a text corpus. Latent topic models, on the other hand, take a more global view, looking at the word distributions across the corpus to assign a topic to each word occurrence. These two paradigms are complementary in how they represent the meaning of word occurrences. While some previous works have already looked at using word embeddings for improving the quality of latent topics, and conversely, at using latent topics for improving word embeddings, such "two-step" methods cannot capture the mutual interaction between the two paradigms. In this paper, we propose STE, a framework which can learn word embeddings and latent topics in a unified manner. STE naturally obtains topic-specific word embeddings, and thus addresses the issue of polysemy. At the same time, it also learns the term distributions of the topics, and the topic distributions of the documents. Our experimental results demonstrate that the STE model can indeed generate useful topic-specific word embeddings and coherent latent topics in an effective and efficient way.

##### Abstract (translated by Google)
诸如Skip-gram之类的字嵌入模型基于在文本语料库中观察到的本地词汇搭配模式来学习每个词的向量空间表示。另一方面，潜在话题模型则采取更为全球化的观点，通过查看整个语料库中的单词分布来为每个单词出现分配一个主题。这两种范式在词汇表达的含义上是相辅相成的。虽然以前的一些作品已经研究了使用词嵌入来提高潜在主题的质量，反之，在使用潜在主题来改善词嵌入时，这种“两步式”的方法不能捕捉到两种范式之间的相互作用。在本文中，我们提出了一个可以统一学习单词嵌入和潜在主题的框架。 STE自然会获得特定于主题的单词嵌入，从而解决多义性的问题。同时学习主题的词汇分布和文档的主题分布。我们的实验结果表明，STE模型确实能够以有效和高效的方式生成有用的特定于主题的词语嵌入和连贯的潜在主题。

##### URL
[https://arxiv.org/abs/1706.07276](https://arxiv.org/abs/1706.07276)

##### PDF
[https://arxiv.org/pdf/1706.07276](https://arxiv.org/pdf/1706.07276)

