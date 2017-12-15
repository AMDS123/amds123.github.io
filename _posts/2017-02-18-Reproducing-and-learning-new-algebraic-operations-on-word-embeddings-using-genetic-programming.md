---
layout: post
title: "Reproducing and learning new algebraic operations on word embeddings using genetic programming"
date: 2017-02-18 15:29:01
categories: arXiv_SD
tags: arXiv_SD Embedding Classification Language_Model Relation
author: Roberto Santana
mathjax: true
---

* content
{:toc}

##### Abstract
Word-vector representations associate a high dimensional real-vector to every word from a corpus. Recently, neural-network based methods have been proposed for learning this representation from large corpora. This type of word-to-vector embedding is able to keep, in the learned vector space, some of the syntactic and semantic relationships present in the original word corpus. This, in turn, serves to address different types of language classification tasks by doing algebraic operations defined on the vectors. The general practice is to assume that the semantic relationships between the words can be inferred by the application of a-priori specified algebraic operations. Our general goal in this paper is to show that it is possible to learn methods for word composition in semantic spaces. Instead of expressing the compositional method as an algebraic operation, we will encode it as a program, which can be linear, nonlinear, or involve more intricate expressions. More remarkably, this program will be evolved from a set of initial random programs by means of genetic programming (GP). We show that our method is able to reproduce the same behavior as human-designed algebraic operators. Using a word analogy task as benchmark, we also show that GP-generated programs are able to obtain accuracy values above those produced by the commonly used human-designed rule for algebraic manipulation of word vectors. Finally, we show the robustness of our approach by executing the evolved programs on the word2vec GoogleNews vectors, learned over 3 billion running words, and assessing their accuracy in the same word analogy task.

##### Abstract (translated by Google)
单词矢量表示将高维实矢量与来自语料库的每个单词相关联。最近，基于神经网络的方法已经被提出用于从大语料库中学习这种表示。这种类型的单词向量嵌入能够在学习的向量空间中保留原始单词语料库中存在的某些句法和语义关系。这反过来又通过在矢量上定义的代数运算来处理不同类型的语言分类任务。一般的做法是假定单词之间的语义关系可以通过应用先验指定的代数运算来推断。本文的总体目标是证明在语义空间中学习单词组合的方法是可能的。我们不是将组合方法表示为代数运算，而是将其编码为一个程序，它可以是线性的，非线性的，或者涉及更复杂的表达式。更为重要的是，这个程序将通过遗传编程（GP）从一套最初的随机程序演化而来。我们表明，我们的方法能够重现与人为设计的代数运算符相同的行为。使用词类比任务作为基准，我们还显示，GP生成的程序能够获得高于通常使用的人为设计的用于词向量的代数运算的规则所产生的准确度值。最后，我们通过在word2vec GoogleNews矢量上执行演化的程序，学习超过30亿个运行的单词，并在相同的单词比喻任务中评估它们的准确性来展示我们的方法的稳健性。

##### URL
[https://arxiv.org/abs/1702.05624](https://arxiv.org/abs/1702.05624)

##### PDF
[https://arxiv.org/pdf/1702.05624](https://arxiv.org/pdf/1702.05624)

