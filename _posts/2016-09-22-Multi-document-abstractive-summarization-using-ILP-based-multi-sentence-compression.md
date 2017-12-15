---
layout: post
title: "Multi-document abstractive summarization using ILP based multi-sentence compression"
date: 2016-09-22 15:51:43
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Siddhartha Banerjee, Prasenjit Mitra, Kazunari Sugiyama
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive summarization is an ideal form of summarization since it can synthesize information from multiple documents to create concise informative summaries. In this work, we aim at developing an abstractive summarizer. First, our proposed approach identifies the most important document in the multi-document set. The sentences in the most important document are aligned to sentences in other documents to generate clusters of similar sentences. Second, we generate K-shortest paths from the sentences in each cluster using a word-graph structure. Finally, we select sentences from the set of shortest paths generated from all the clusters employing a novel integer linear programming (ILP) model with the objective of maximizing information content and readability of the final summary. Our ILP model represents the shortest paths as binary variables and considers the length of the path, information score and linguistic quality score in the objective function. Experimental results on the DUC 2004 and 2005 multi-document summarization datasets show that our proposed approach outperforms all the baselines and state-of-the-art extractive summarizers as measured by the ROUGE scores. Our method also outperforms a recent abstractive summarization technique. In manual evaluation, our approach also achieves promising results on informativeness and readability.

##### Abstract (translated by Google)
抽象概括是一种理想的摘要形式，因为它可以综合来自多个文档的信息以创建简明的信息摘要。在这项工作中，我们的目标是开发一个抽象概述。首先，我们提出的方法确定了多文档集中最重要的文档。最重要的文档中的句子与其他文档中的句子对齐，以生成类似句子的聚类。其次，我们使用一个字 - 图结构从每个集群中的句子生成K-最短路径。最后，我们从所有使用新型整数线性规划（ILP）模型的集群生成的最短路径中选择句子，目的是最大化信息内容和最终总结的可读性。我们的ILP模型将最短路径表示为二元变量，并在目标函数中考虑路径的长度，信息得分和语言质量得分。在DUC 2004和2005多文档摘要数据集上的实验结果表明，我们提出的方法优于ROUGE得分所测量的所有基线和最先进的抽取摘要。我们的方法也胜过最近的抽象概括技术。在手动评估中，我们的方法在信息性和可读性方面也取得了有希望的结果。

##### URL
[https://arxiv.org/abs/1609.07034](https://arxiv.org/abs/1609.07034)

##### PDF
[https://arxiv.org/pdf/1609.07034](https://arxiv.org/pdf/1609.07034)

