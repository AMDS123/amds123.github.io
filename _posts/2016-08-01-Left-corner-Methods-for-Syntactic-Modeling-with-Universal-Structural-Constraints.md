---
layout: post
title: "Left-corner Methods for Syntactic Modeling with Universal Structural Constraints"
date: 2016-08-01 01:18:53
categories: arXiv_CL
tags: arXiv_CL Salient Embedding
author: Hiroshi Noji
mathjax: true
---

* content
{:toc}

##### Abstract
The primary goal in this thesis is to identify better syntactic constraint or bias, that is language independent but also efficiently exploitable during sentence processing. We focus on a particular syntactic construction called center-embedding, which is well studied in psycholinguistics and noted to cause particular difficulty for comprehension. Since people use language as a tool for communication, one expects such complex constructions to be avoided for communication efficiency. From a computational perspective, center-embedding is closely relevant to a left-corner parsing algorithm, which can capture the degree of center-embedding of a parse tree being constructed. This connection suggests left-corner methods can be a tool to exploit the universal syntactic constraint that people avoid generating center-embedded structures. We explore such utilities of center-embedding as well as left-corner methods extensively through several theoretical and empirical examinations. Our primary task is unsupervised grammar induction. In this task, the input to the algorithm is a collection of sentences, from which the model tries to extract the salient patterns on them as a grammar. This is a particularly hard problem although we expect the universal constraint may help in improving the performance since it can effectively restrict the possible search space for the model. We build the model by extending the left-corner parsing algorithm for efficiently tabulating the search space except those involving center-embedding up to a specific degree. We examine the effectiveness of our approach on many treebanks, and demonstrate that often our constraint leads to better parsing performance. We thus conclude that left-corner methods are particularly useful for syntax-oriented systems, as it can exploit efficiently the inherent universal constraints in languages.

##### Abstract (translated by Google)
本文的主要目标是找出更好的句法约束或偏见，即语言独立性，而且在句子处理过程中也可以有效利用。我们专注于一种称为中心嵌入的特定句法结构，这种结构在心理语言学方面已经得到很好的研究，并被认为会给理解带来特殊的困难。由于人们使用语言作为交流工具，所以人们期望这种复杂的结构可以避免交流的效率。从计算的角度来看，中心嵌入与左边的解析算法密切相关，可以捕捉正在构建的解析树的中心嵌入度。这种联系表明左转角方法可以成为利用通用语法约束的工具，人们避免生成中心嵌入结构。我们通过几个理论和实证考察，广泛探讨了中心嵌入和左角点方法。我们的主要任务是无监督的语法感应。在这个任务中，算法的输入是一个句子的集合，从这个句子中，模型试图将它们的显着模式作为语法来提取。这是一个特别困难的问题，尽管我们期望通用约束可能有助于提高性能，因为它可以有效地限制模型的可能搜索空间。我们通过扩展左角解析算法来构建模型，以有效地对除了涉及中心嵌入到特定程度的搜索空间进行制表。我们研究了我们的方法在许多树库上的有效性，并且证明了我们的约束常常导致更好的解析性能。因此，我们得出这样的结论：左边角方法对于面向语法的系统特别有用，因为它可以有效地利用语言中固有的通用约束。

##### URL
[https://arxiv.org/abs/1608.00293](https://arxiv.org/abs/1608.00293)

##### PDF
[https://arxiv.org/pdf/1608.00293](https://arxiv.org/pdf/1608.00293)

