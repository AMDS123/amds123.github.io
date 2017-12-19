---
layout: post
title: "sense2vec - A Fast and Accurate Method for Word Sense Disambiguation In Neural Word Embeddings"
date: 2015-11-19 21:22:42
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Andrew Trask, Phil Michalak, John Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural word representations have proven useful in Natural Language Processing (NLP) tasks due to their ability to efficiently model complex semantic and syntactic word relationships. However, most techniques model only one representation per word, despite the fact that a single word can have multiple meanings or "senses". Some techniques model words by using multiple vectors that are clustered based on context. However, recent neural approaches rarely focus on the application to a consuming NLP algorithm. Furthermore, the training process of recent word-sense models is expensive relative to single-sense embedding processes. This paper presents a novel approach which addresses these concerns by modeling multiple embeddings for each word based on supervised disambiguation, which provides a fast and accurate way for a consuming NLP model to select a sense-disambiguated embedding. We demonstrate that these embeddings can disambiguate both contrastive senses such as nominal and verbal senses as well as nuanced senses such as sarcasm. We further evaluate Part-of-Speech disambiguated embeddings on neural dependency parsing, yielding a greater than 8% average error reduction in unlabeled attachment scores across 6 languages.

##### Abstract (translated by Google)
神经词表示在自然语言处理（NLP）任务中被证明是有用的，因为它们能够有效地建立复杂的语义和句法单词关系。然而，尽管事实上一个单词可以有多重含义或“感觉”，但大多数技巧只能为每个单词建模一个表示。一些技术通过使用基于上下文聚集的多个向量对单词进行建模。然而，最近的神经方法很少关注于消费NLP算法的应用。而且，相对于单义嵌入过程，最近的词义模型的训练过程是昂贵的。本文提出了一种新颖的方法来解决这些问题，通过基于监督消歧为每个单词建模多个嵌入，为消费NLP模型提供快速而准确的方法来选择一个消歧的嵌入。我们证明，这些嵌入可以消除歧义的感官，如名义和口头的感官，以及细微的感官，如讽刺。我们进一步评估了部分语义歧义消除嵌入神经依赖性分析，在6种语言的非标签附件分数产生平均错误减少8％以上。

##### URL
[https://arxiv.org/abs/1511.06388](https://arxiv.org/abs/1511.06388)

##### PDF
[https://arxiv.org/pdf/1511.06388](https://arxiv.org/pdf/1511.06388)

