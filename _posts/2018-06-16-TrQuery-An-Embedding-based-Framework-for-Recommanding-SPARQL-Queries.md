---
layout: post
title: "TrQuery: An Embedding-based Framework for Recommanding SPARQL Queries"
date: 2018-06-16 08:17:08
categories: arXiv_AI
tags: arXiv_AI Embedding Recommendation
author: Lijing Zhang, Xiaowang Zhang, Zhiyong Feng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an embedding-based framework (TrQuery) for recommending solutions of a SPARQL query, including approximate solutions when exact querying solutions are not available due to incompleteness or inconsistencies of real-world RDF data. Within this framework, embedding is applied to score solutions together with edit distance so that we could obtain more fine-grained recommendations than those recommendations via edit distance. For instance, graphs of two querying solutions with a similar structure can be distinguished in our proposed framework while the edit distance depending on structural difference becomes unable. To this end, we propose a novel score model built on vector space generated in embedding system to compute the similarity between an approximate subgraph matching and a whole graph matching. Finally, we evaluate our approach on large RDF datasets DBpedia and YAGO, and experimental results show that TrQuery exhibits an excellent behavior in terms of both effectiveness and efficiency.

##### Abstract (translated by Google)
在本文中，我们提出了一个基于嵌入的框架（TrQuery），用于推荐SPARQL查询的解决方案，其中包括由于实际RDF数据的不完整性或不一致性导致无法提供精确查询解决方案时的近似解决方案。在这个框架中，嵌入被用于将解决方案与编辑距离一起评分，以便我们可以获得比通过编辑距离的建议更精细的建议。例如，在我们提出的框架中，可以区分具有相似结构的两个查询解的图形，而取决于结构差异的编辑距离变得不可行。为此，我们提出了一种基于嵌入系统中生成的向量空间构建的新的评分模型，用于计算近似子图匹配和整体图匹配之间的相似度。最后，我们评估了我们在大型RDF数据库DBpedia和YAGO上的方法，实验结果表明，TrQuery在有效性和效率方面表现出优异的行为。

##### URL
[http://arxiv.org/abs/1806.06205](http://arxiv.org/abs/1806.06205)

##### PDF
[http://arxiv.org/pdf/1806.06205](http://arxiv.org/pdf/1806.06205)

