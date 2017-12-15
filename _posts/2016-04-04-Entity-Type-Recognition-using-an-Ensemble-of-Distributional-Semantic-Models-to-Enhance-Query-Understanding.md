---
layout: post
title: "Entity Type Recognition using an Ensemble of Distributional Semantic Models to Enhance Query Understanding"
date: 2016-04-04 16:18:44
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding Language_Model Recognition
author: Walid Shalaby, Khalifeh Al Jadda, Mohammed Korayem, Trey Grainger
mathjax: true
---

* content
{:toc}

##### Abstract
We present an ensemble approach for categorizing search query entities in the recruitment domain. Understanding the types of entities expressed in a search query (Company, Skill, Job Title, etc.) enables more intelligent information retrieval based upon those entities compared to a traditional keyword-based search. Because search queries are typically very short, leveraging a traditional bag-of-words model to identify entity types would be inappropriate due to the lack of contextual information. Our approach instead combines clues from different sources of varying complexity in order to collect real-world knowledge about query entities. We employ distributional semantic representations of query entities through two models: 1) contextual vectors generated from encyclopedic corpora like Wikipedia, and 2) high dimensional word embedding vectors generated from millions of job postings using word2vec. Additionally, our approach utilizes both entity linguistic properties obtained from WordNet and ontological properties extracted from DBpedia. We evaluate our approach on a data set created at CareerBuilder; the largest job board in the US. The data set contains entities extracted from millions of job seekers/recruiters search queries, job postings, and resume documents. After constructing the distributional vectors of search entities, we use supervised machine learning to infer search entity types. Empirical results show that our approach outperforms the state-of-the-art word2vec distributional semantics model trained on Wikipedia. Moreover, we achieve micro-averaged F 1 score of 97% using the proposed distributional representations ensemble.

##### Abstract (translated by Google)
我们提出一个集合的方法来分类搜索查询实体在招聘领域。了解在搜索查询（公司，技能，职位等）中表达的实体类型，与传统的基于关键字的搜索相比，可以基于这些实体进行更智能的信息检索。由于搜索查询通常非常短，因缺乏上下文信息，利用传统的词袋模型来识别实体类型将是不适当的。我们的方法是结合来自不同复杂性来源的线索，以收集关于查询实体的真实世界的知识。我们通过两种模式使用查询实体的分布式语义表示：1）从百科全书库（如Wikipedia）生成的上下文向量; 2）使用word2vec从数百万个招贴中生成的高维词嵌入向量。另外，我们的方法利用从WordNet获得的实体语言属性和从DBpedia提取的本体属性。我们在CareerBuilder创建的数据集上评估我们的方法;在美国最大的工作董事会。数据集包含从数百万求职者/招聘者搜索查询中提取的实体，招聘信息和简历文档。在构造搜索实体的分布向量之后，我们使用有监督的机器学习来推断搜索实体类型。实证结果表明，我们的方法胜过维基百科上训练的最先进的word2vec分布式语义模型。此外，我们使用所提出的分布表示集合来实现97％的微平均F 1得分。

##### URL
[https://arxiv.org/abs/1604.00933](https://arxiv.org/abs/1604.00933)

##### PDF
[https://arxiv.org/pdf/1604.00933](https://arxiv.org/pdf/1604.00933)

