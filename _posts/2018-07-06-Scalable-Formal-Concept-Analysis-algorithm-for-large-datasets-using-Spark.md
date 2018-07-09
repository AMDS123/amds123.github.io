---
layout: post
title: "Scalable Formal Concept Analysis algorithm for large datasets using Spark"
date: 2018-07-06 05:22:31
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Raghavendra K Chunduri, Aswani Kumar Cherukuri
mathjax: true
---

* content
{:toc}

##### Abstract
In the process of knowledge discovery and representation in large datasets using formal concept analysis, complexity plays a major role in identifying all the formal concepts and constructing the concept lattice(digraph of the concepts). For identifying the formal concepts and constructing the digraph from the identified concepts in very large datasets, various distributed algorithms are available in the literature. However, the existing distributed algorithms are not very well suitable for concept generation because it is an iterative process. The existing algorithms are implemented using distributed frameworks like MapReduce and Open MP, these frameworks are not appropriate for iterative applications. Hence, in this paper we proposed efficient distributed algorithms for both formal concept generation and concept lattice digraph construction in large formal contexts using Apache Spark. Various performance metrics are considered for the evaluation of the proposed work, the results of the evaluation proves that the proposed algorithms are efficient for concept generation and lattice graph construction in comparison with the existing algorithms.

##### Abstract (translated by Google)
在使用形式概念分析的大型数据集中进行知识发现和表示的过程中，复杂性在识别所有形式概念和构建概念格（构图概念）中起着重要作用。为了识别形式概念并从非常大的数据集中的已识别概念构建有向图，文献中提供了各种分布式算法。然而，现有的分布式算法不太适合于概念生成，因为它是一个迭代过程。现有算法使用MapReduce和Open MP等分布式框架实现，这些框架不适合迭代应用程序。因此，在本文中，我们使用Apache Spark在大型正式上下文中为形式概念生成和概念格图集构造提出了有效的分布式算法。考虑各种性能指标用于评估所提出的工作，评估结果证明所提出的算法与现有算法相比对于概念生成和点阵图构造是有效的。

##### URL
[http://arxiv.org/abs/1807.02258](http://arxiv.org/abs/1807.02258)

##### PDF
[http://arxiv.org/pdf/1807.02258](http://arxiv.org/pdf/1807.02258)

