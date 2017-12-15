---
layout: post
title: "Multilingual Knowledge Graph Embeddings for Cross-lingual Knowledge Alignment"
date: 2017-05-17 19:33:53
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Embedding Relation
author: Muhao Chen, Yingtao Tian, Mohan Yang, Carlo Zaniolo
mathjax: true
---

* content
{:toc}

##### Abstract
Many recent works have demonstrated the benefits of knowledge graph embeddings in completing monolingual knowledge graphs. Inasmuch as related knowledge bases are built in several different languages, achieving cross-lingual knowledge alignment will help people in constructing a coherent knowledge base, and assist machines in dealing with different expressions of entity relationships across diverse human languages. Unfortunately, achieving this highly desirable crosslingual alignment by human labor is very costly and errorprone. Thus, we propose MTransE, a translation-based model for multilingual knowledge graph embeddings, to provide a simple and automated solution. By encoding entities and relations of each language in a separated embedding space, MTransE provides transitions for each embedding vector to its cross-lingual counterparts in other spaces, while preserving the functionalities of monolingual embeddings. We deploy three different techniques to represent cross-lingual transitions, namely axis calibration, translation vectors, and linear transformations, and derive five variants for MTransE using different loss functions. Our models can be trained on partially aligned graphs, where just a small portion of triples are aligned with their cross-lingual counterparts. The experiments on cross-lingual entity matching and triple-wise alignment verification show promising results, with some variants consistently outperforming others on different tasks. We also explore how MTransE preserves the key properties of its monolingual counterpart TransE.

##### Abstract (translated by Google)
许多最近的作品已经证明了知识图嵌入在完成单语知识图中的好处。由于相关的知识库是用不同的语言建立起来的，所以实现跨语言的知识对齐将有助于人们构建一个连贯的知识库，并协助机器处理跨不同人类语言的不同实体关系表达。不幸的是，通过人力来实现这种非常理想的跨语言对齐是非常昂贵和错误的。因此，我们提出MTransE，一个多语言知识图嵌入的基于翻译的模型，提供一个简单和自动的解决方案。通过在分开的嵌入空间编码实体和每种语言的关系，MTransE提供转换为每个嵌入载体能够在其他空间其跨语言对应，同时保留单语的嵌入的功能。我们使用三种不同的技术来表示跨语言转换，即轴校准，平移向量和线性转换，并使用不同的损失函数推导出MTransE的五个变体。我们的模型可以在部分对齐的图上进行训练，其中只有一小部分三元组与他们的跨语言对应对齐。跨语言实体匹配和三重对齐验证的实验显示出了令人鼓舞的结果，其中一些变体在不同的任务上始终如一地胜过其他变体。我们还探索MTransE如何保留单语对应TransE的关键属性。

##### URL
[https://arxiv.org/abs/1611.03954](https://arxiv.org/abs/1611.03954)

##### PDF
[https://arxiv.org/pdf/1611.03954](https://arxiv.org/pdf/1611.03954)

