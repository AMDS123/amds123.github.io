---
layout: post
title: "Enabling Cognitive Intelligence Queries in Relational Databases using Low-dimensional Word Embeddings"
date: 2016-03-23 13:57:33
categories: arXiv_SD
tags: arXiv_SD Embedding Relation
author: Rajesh Bordawekar, Oded Shmueli
mathjax: true
---

* content
{:toc}

##### Abstract
We apply distributed language embedding methods from Natural Language Processing to assign a vector to each database entity associated token (for example, a token may be a word occurring in a table row, or the name of a column). These vectors, of typical dimension 200, capture the meaning of tokens based on the contexts in which the tokens appear together. To form vectors, we apply a learning method to a token sequence derived from the database. We describe various techniques for extracting token sequences from a database. The techniques differ in complexity, in the token sequences they output and in the database information used (e.g., foreign keys). The vectors can be used to algebraically quantify semantic relationships between the tokens such as similarities and analogies. Vectors enable a dual view of the data: relational and (meaningful rather than purely syntactical) text. We introduce and explore a new class of queries called cognitive intelligence (CI) queries that extract information from the database based, in part, on the relationships encoded by vectors. We have implemented a prototype system on top of Spark to exhibit the power of CI queries. Here, CI queries are realized via SQL UDFs. This power goes far beyond text extensions to relational systems due to the information encoded in vectors. We also consider various extensions to the basic scheme, including using a collection of views derived from the database to focus on a domain of interest, utilizing vectors and/or text from external sources, maintaining vectors as the database evolves and exploring a database without utilizing its schema. For the latter, we consider minimal extensions to SQL to vastly improve query expressiveness.

##### Abstract (translated by Google)
我们使用自然语言处理的分布式语言嵌入方法为每个数据库实体关联的标记（例如，标记可能是表行中发生的一个词，或列的名称）分配一个向量。典型尺寸200的这些向量基于令牌出现在一起的上下文来捕捉令牌的含义。为了形成向量，我们将一个学习方法应用于从数据库派生的令牌序列。我们描述了从数据库中提取令牌序列的各种技术。这些技术在复杂性，它们输出的令牌序列和使用的数据库信息（例如，外键）方面不同。向量可用于代数化量化令牌之间的语义关系，如相似性和类比。向量启用数据的双重视图：关系和（有意义的而不是纯粹的语法）文本。我们引入并探索一类称为认知智能（CI）查询的新型查询，这些查询从数据库中提取信息，部分基于由矢量编码的关系。我们在Spark的顶部实现了一个原型系统，展现CI查询的强大功能。在这里，CI查询是通过SQL UDF实现的。由于向量中编码的信息，这种能力远远超出了关系系统的文本扩展。我们还考虑了对基本方案的各种扩展，包括使用来自数据库的视图集合来关注感兴趣的领域，利用来自外部源的矢量和/或文本，随着数据库的发展维护矢量，并且探索数据库而不利用其架构。对于后者，我们考虑对SQL进行最小限度的扩展以大大提高查询表达能力。

##### URL
[https://arxiv.org/abs/1603.07185](https://arxiv.org/abs/1603.07185)

##### PDF
[https://arxiv.org/pdf/1603.07185](https://arxiv.org/pdf/1603.07185)

