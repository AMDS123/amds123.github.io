---
layout: post
title: "Traversing Knowledge Graphs in Vector Space"
date: 2015-08-19 05:16:24
categories: arXiv_CL
tags: arXiv_CL Regularization Knowledge_Graph Knowledge Embedding
author: Kelvin Guu, John Miller, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Path queries on a knowledge graph can be used to answer compositional questions such as "What languages are spoken by people living in Lisbon?". However, knowledge graphs often have missing facts (edges) which disrupts path queries. Recent models for knowledge base completion impute missing facts by embedding knowledge graphs in vector spaces. We show that these models can be recursively applied to answer path queries, but that they suffer from cascading errors. This motivates a new "compositional" training objective, which dramatically improves all models' ability to answer path queries, in some cases more than doubling accuracy. On a standard knowledge base completion task, we also demonstrate that compositional training acts as a novel form of structural regularization, reliably improving performance across all base models (reducing errors by up to 43%) and achieving new state-of-the-art results.

##### Abstract (translated by Google)
在知识图上的路径查询可以用来回答组成性问题，例如“在里斯本居住的人使用什么语言？”。然而，知识图通常缺少破坏路径查询的事实（边缘）。最近的知识库完成模型通过将知识图嵌入到向量空间中来推断缺少的事实。我们表明，这些模型可以递归地应用于回答路径查询，但他们遭受级联错误。这激发了一个新的“组合”培训目标，这大大提高了所有模型回答路径查询的能力，在某些情况下精度提高了一倍以上。在一个标准的知识库完成任务中，我们还证明了组合训练是一种新颖的结构正则化形式，可以在所有基础模型中可靠地提高性能（减少高达43％的错误）并获得最新的最新结果。

##### URL
[https://arxiv.org/abs/1506.01094](https://arxiv.org/abs/1506.01094)

##### PDF
[https://arxiv.org/pdf/1506.01094](https://arxiv.org/pdf/1506.01094)

