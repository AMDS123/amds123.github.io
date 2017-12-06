---
layout: post
title: 'AMC: Attention guided Multi-modal Correlation Learning for Image Search'
date: 2017-04-03 18:57:42
categories: arXiv_CV
tags: arXiv_CV Caption
author: Kan Chen, Trung Bui, Fang Chen, Zhaowen Wang, Ram Nevatia
---

* content
{:toc}

##### Abstract
Given a user's query, traditional image search systems rank images according to its relevance to a single modality (e.g., image content or surrounding text). Nowadays, an increasing number of images on the Internet are available with associated meta data in rich modalities (e.g., titles, keywords, tags, etc.), which can be exploited for better similarity measure with queries. In this paper, we leverage visual and textual modalities for image search by learning their correlation with input query. According to the intent of query, attention mechanism can be introduced to adaptively balance the importance of different modalities. We propose a novel Attention guided Multi-modal Correlation (AMC) learning method which consists of a jointly learned hierarchy of intra and inter-attention networks. Conditioned on query's intent, intra-attention networks (i.e., visual intra-attention network and language intra-attention network) attend on informative parts within each modality; a multi-modal inter-attention network promotes the importance of the most query-relevant modalities. In experiments, we evaluate AMC models on the search logs from two real world image search engines and show a significant boost on the ranking of user-clicked images in search results. Additionally, we extend AMC models to caption ranking task on COCO dataset and achieve competitive results compared with recent state-of-the-arts.

##### Abstract (translated by Google)
给定用户的查询，传统图像搜索系统根据其与单一模态（例如，图像内容或周围文本）的相关性对图像进行排序。目前，互联网上越来越多的图像可以与丰富的模式（例如，标题，关键词，标签等）中的相关联的元数据一起使用，其可以被利用来与查询进行更好的相似性度量。在本文中，我们利用视觉和文本的形式进行图像搜索，通过学习与输入查询的相关性。根据查询的意图，可以引入注意机制来自适应地平衡不同模式的重要性。我们提出了一种新颖的注意引导多模态相关（AMC）学习方法，它由一个共同学习的内部和关注网络的层次组成。在查询意图条件下，注意力网络（即视觉注意力网络和语言注意力网络）参加每种模态内的信息部分;一个多模式的相互关注网络促进了大多数查询相关的模式的重要性。在实验中，我们从两个真实世界的图像搜索引擎的搜索日志评估AMC模型，显示在搜索结果中用户点击图像的排名显着提升。此外，我们将AMC模型扩展到COCO数据集上的标题排序任务，并与最近的最新技术相比取得竞争结果。

##### URL
[https://arxiv.org/abs/1704.00763](https://arxiv.org/abs/1704.00763)

