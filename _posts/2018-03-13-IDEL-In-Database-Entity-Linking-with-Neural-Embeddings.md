---
layout: post
title: "IDEL: In-Database Entity Linking with Neural Embeddings"
date: 2018-03-13 15:35:42
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Relation
author: Torsten Kilias, Alexander L&#xf6;ser, Felix A. Gers, Richard Koopmanschap, Ying Zhang, Martin Kersten
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel architecture, In-Database Entity Linking (IDEL), in which we integrate the analytics-optimized RDBMS MonetDB with neural text mining abilities. Our system design abstracts core tasks of most neural entity linking systems for MonetDB. To the best of our knowledge, this is the first defacto implemented system integrating entity-linking in a database. We leverage the ability of MonetDB to support in-database-analytics with user defined functions (UDFs) implemented in Python. These functions call machine learning libraries for neural text mining, such as TensorFlow. The system achieves zero cost for data shipping and transformation by utilizing MonetDB's ability to embed Python processes in the database kernel and exchange data in NumPy arrays. IDEL represents text and relational data in a joint vector space with neural embeddings and can compensate errors with ambiguous entity representations. For detecting matching entities, we propose a novel similarity function based on joint neural embeddings which are learned via minimizing pairwise contrastive ranking loss. This function utilizes a high dimensional index structures for fast retrieval of matching entities. Our first implementation and experiments using the WebNLG corpus show the effectiveness and the potentials of IDEL.

##### Abstract (translated by Google)
我们提出了一种新颖的架构，即数据库内实体链接（IDEL），我们将分析优化的RDBMS MonetDB与神经文本挖掘功能集成在一起。我们的系统设计为MonetDB提供了大部分神经实体链接系统的核心任务。就我们所知，这是第一个事实上实现的系统，它将数据库中的实体链接集成在一起。我们利用MonetDB支持用Python实现的用户定义函数（UDF）进行数据库内分析的能力。这些函数调用用于神经文本挖掘的机器学习库，例如TensorFlow。通过利用MonetDB将Python进程嵌入数据库内核并在NumPy数组中交换数据的能力，该系统实现了数据传输和转换的零成本。 IDEL代表联合向量空间中的文本和关系数据以及神经嵌入，并且可以用不明确的实体表示来补偿错误。为了检测匹配实体，我们提出了一种基于联合神经嵌入的新型相似函数，通过最小化成对比较排序损失来学习联合神经嵌入。该功能利用高维索引结构来快速检索匹配实体。我们首次使用WebNLG语料库进行实施和实验显示了IDEL的有效性和潜力。

##### URL
[http://arxiv.org/abs/1803.04884](http://arxiv.org/abs/1803.04884)

##### PDF
[http://arxiv.org/pdf/1803.04884](http://arxiv.org/pdf/1803.04884)

