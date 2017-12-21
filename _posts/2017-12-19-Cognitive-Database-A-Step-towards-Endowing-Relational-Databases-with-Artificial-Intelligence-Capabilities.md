---
layout: post
title: "Cognitive Database: A Step towards Endowing Relational Databases with Artificial Intelligence Capabilities"
date: 2017-12-19 20:49:26
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Relation
author: Rajesh Bordawekar, Bortik Bandyopadhyay, Oded Shmueli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Cognitive Databases, an approach for transparently enabling Artificial Intelligence (AI) capabilities in relational databases. A novel aspect of our design is to first view the structured data source as meaningful unstructured text, and then use the text to build an unsupervised neural network model using a Natural Language Processing (NLP) technique called word embedding. This model captures the hidden inter-/intra-column relationships between database tokens of different types. For each database token, the model includes a vector that encodes contextual semantic relationships. We seamlessly integrate the word embedding model into existing SQL query infrastructure and use it to enable a new class of SQL-based analytics queries called cognitive intelligence (CI) queries. CI queries use the model vectors to enable complex queries such as semantic matching, inductive reasoning queries such as analogies, predictive queries using entities not present in a database, and, more generally, using knowledge from external sources. We demonstrate unique capabilities of Cognitive Databases using an Apache Spark based prototype to execute inductive reasoning CI queries over a multi-modal database containing text and images. We believe our first-of-a-kind system exemplifies using AI functionality to endow relational databases with capabilities that were previously very hard to realize in practice.

##### Abstract (translated by Google)
我们提出认知数据库，这是一种在关系数据库中透明地实现人工智能（AI）功能的方法。我们设计的一个新颖方面是首先将结构化数据源视为有意义的非结构化文本，然后使用称为词嵌入的自然语言处理（NLP）技术，使用文本构建无监督神经网络模型。该模型捕获不同类型的数据库令牌之间隐藏的列间/列内关系。对于每个数据库令牌，该模型包括一个编码上下文语义关系的向量。我们无缝地将单词嵌入模型集成到现有的SQL查询基础架构中，并使用它来启用称为认知智能（CI）查询的新一类基于SQL的分析查询。 CI查询使用模型向量来实现诸如语义匹配之类的复杂查询，诸如类比之类的归纳推理查询，使用数据库中不存在的实体的预测查询，以及更一般地使用来自外部来源的知识。我们展示了独特的认知数据库功能，使用基于Apache Spark的原型，通过包含文本和图像的多模式数据库执行归纳推理CI查询。我们相信我们的第一个系统体现了使用AI功能来赋予关系数据库以前在实践中很难实现的功能。

##### URL
[https://arxiv.org/abs/1712.07199](https://arxiv.org/abs/1712.07199)

##### PDF
[https://arxiv.org/pdf/1712.07199](https://arxiv.org/pdf/1712.07199)

