---
layout: post
title: "Bridging the Gap: Incorporating a Semantic Similarity Measure for Effectively Mapping PubMed Queries to Documents"
date: 2017-10-17 19:33:57
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Sun Kim, Nicolas Fiorini, W. John Wilbur, Zhiyong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
The main approach of traditional information retrieval (IR) is to examine how many words from a query appear in a document. A drawback of this approach, however, is that it may fail to detect relevant documents where no or only few words from a query are found. The semantic analysis methods such as LSA (latent semantic analysis) and LDA (latent Dirichlet allocation) have been proposed to address the issue, but their performance is not superior compared to common IR approaches. Here we present a query-document similarity measure motivated by the Word Mover's Distance. Unlike other similarity measures, the proposed method relies on neural word embeddings to compute the distance between words. This process helps identify related words when no direct matches are found between a query and a document. Our method is efficient and straightforward to implement. The experimental results on TREC Genomics data show that our approach outperforms the BM25 ranking function by an average of 12% in mean average precision. Furthermore, for a real-world dataset collected from the PubMed search logs, we combine the semantic measure with BM25 using a learning to rank method, which leads to improved ranking scores by up to 25%. This experiment demonstrates that the proposed approach and BM25 nicely complement each other and together produce superior performance.

##### Abstract (translated by Google)
传统信息检索（IR）的主要方法是检查一个查询中有多少单词出现在文档中。然而，这种方法的一个缺点是它可能无法检测到相关的文档，在这些文档中没有发现或者只有少量的查询词。已经提出了诸如LSA（潜在语义分析）和LDA（潜在Dirichlet分配）之类的语义分析方法来解决这个问题，但是它们的性能与普通的IR方法相比并不优越。在这里，我们提出一个查询 - 文档相似性度量的动机的移动距离。与其他相似性度量不同，所提出的方法依赖于神经词嵌入来计算词之间的距离。当在查询和文档之间没有找到直接匹配时，这个过程帮助识别相关词汇。我们的方法是高效和直接的实施。 TREC基因组学数据的实验结果表明，我们的方法在均值平均精度上平均优于BM25排序函数12％。此外，对于从PubMed搜索日志中收集的真实世界的数据集，我们使用学习排序方法将语义测量与BM25相结合，从而将排名分数提高了25％。这个实验表明，提出的方法和BM25很好地相辅相成，并且共同产生出色的性能。

##### URL
[https://arxiv.org/abs/1608.01972](https://arxiv.org/abs/1608.01972)

##### PDF
[https://arxiv.org/pdf/1608.01972](https://arxiv.org/pdf/1608.01972)

