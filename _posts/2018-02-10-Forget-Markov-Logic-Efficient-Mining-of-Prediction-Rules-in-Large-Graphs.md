---
layout: post
title: "Forget Markov Logic: Efficient Mining of Prediction Rules in Large Graphs"
date: 2018-02-10 18:46:54
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Inference Prediction
author: Tommaso Soru, Andr&#xe9; Valdestilhas, Edgard Marx, Axel-Cyrille Ngonga Ngomo
mathjax: true
---

* content
{:toc}

##### Abstract
Graph representations of large knowledge bases may comprise billions of edges. Usually built upon human-generated ontologies, several knowledge bases do not feature declared ontological rules and are far from being complete. Current rule mining approaches rely on schemata or store the graph in-memory, which can be unfeasible for large graphs. In this paper, we introduce HornConcerto, an algorithm to discover Horn clauses in large graphs without the need of a schema. Using a standard fact-based confidence score, we can mine close Horn rules having an arbitrary body size. We show that our method can outperform existing approaches in terms of runtime and memory consumption and mine high-quality rules for the link prediction task, achieving state-of-the-art results on a widely-used benchmark. Moreover, we find that rules alone can perform inference significantly faster than embedding-based methods and achieve accuracies on link prediction comparable to resource-demanding approaches such as Markov Logic Networks.

##### Abstract (translated by Google)
大型知识库的图表表示可能包含数十亿条边界。通常建立在人类本体论的基础上，一些知识库不具有已申明的本体论规则，而且还远未完成。目前的规则挖掘方法依赖图式或将图存储在内存中，这对于大型图而言是不可行的。在本文中，我们介绍HornConcerto，一种在大图中发现Horn子句的算法，而不需要模式。使用标准的基于事实的置信度分数，我们可以挖掘具有任意体大小的关闭Horn规则。我们证明，我们的方法在运行时间和内存消耗方面可以超越现有的方法，并为链接预测任务挖掘高质量的规则，从而在广泛使用的基准测试中获得最新的结果。此外，我们发现单独的规则可以比基于嵌入的方法明显更快地执行推理，并且可以实现链接预测的准确性，与马科夫逻辑网络等资源要求较高的方法相媲美。

##### URL
[http://arxiv.org/abs/1802.03638](http://arxiv.org/abs/1802.03638)

##### PDF
[http://arxiv.org/pdf/1802.03638](http://arxiv.org/pdf/1802.03638)

