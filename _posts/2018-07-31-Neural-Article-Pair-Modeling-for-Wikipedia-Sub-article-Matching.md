---
layout: post
title: "Neural Article Pair Modeling for Wikipedia Sub-article Matching"
date: 2018-07-31 07:19:36
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Muhao Chen, Changping Meng, Gang Huang, Carlo Zaniolo
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, editors tend to separate different subtopics of a long Wiki-pedia article into multiple sub-articles. This separation seeks to improve human readability. However, it also has a deleterious effect on many Wikipedia-based tasks that rely on the article-as-concept assumption, which requires each entity (or concept) to be described solely by one article. This underlying assumption significantly simplifies knowledge representation and extraction, and it is vital to many existing technologies such as automated knowledge base construction, cross-lingual knowledge alignment, semantic search and data lineage of Wikipedia entities. In this paper we provide an approach to match the scattered sub-articles back to their corresponding main-articles, with the intent of facilitating automated Wikipedia curation and processing. The proposed model adopts a hierarchical learning structure that combines multiple variants of neural document pair encoders with a comprehensive set of explicit features. A large crowdsourced dataset is created to support the evaluation and feature extraction for the task. Based on the large dataset, the proposed model achieves promising results of cross-validation and significantly outperforms previous approaches. Large-scale serving on the entire English Wikipedia also proves the practicability and scalability of the proposed model by effectively extracting a vast collection of newly paired main and sub-articles.

##### Abstract (translated by Google)
如今，编辑们倾向于将长篇Wiki-pedia文章的不同副主题分成多个子文章。这种分离旨在提高人类的可读性。然而，它也对许多基于维基百科的任务产生了有害影响，这些任务依赖于作为概念的文章假设，该假设要求每个实体（或概念）仅由一篇文章描述。这一基本假设大大简化了知识表示和提取，对于许多现有技术至关重要，如自动知识库构建，跨语言知识对齐，语义搜索和维基百科实体的数据沿袭。在本文中，我们提供了一种方法，将分散的子文章与其相应的主文章相匹配，旨在促进自动维基百科的策划和处理。所提出的模型采用分层学习结构，其将神经文档对编码器的多个变体与一组全面的显式特征组合。创建大型众包数据集以支持任务的评估和特征提取。基于大型数据集，所提出的模型实现了有希望的交叉验证结果，并且明显优于以前的方法。整个英语维基百科上的大规模服务也通过有效地提取大量新配对的主要和子文章来证明所提出的模型的实用性和可扩展性。

##### URL
[http://arxiv.org/abs/1807.11689](http://arxiv.org/abs/1807.11689)

##### PDF
[http://arxiv.org/pdf/1807.11689](http://arxiv.org/pdf/1807.11689)

