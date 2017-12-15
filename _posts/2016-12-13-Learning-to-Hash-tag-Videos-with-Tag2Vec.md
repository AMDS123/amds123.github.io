---
layout: post
title: "Learning to Hash-tag Videos with Tag2Vec"
date: 2016-12-13 08:32:02
categories: arXiv_CL
tags: arXiv_CL Embedding Quantitative Recommendation
author: Aditya Singh, Saurabh Saini, Rajvi Shah, PJ Narayanan
mathjax: true
---

* content
{:toc}

##### Abstract
User-given tags or labels are valuable resources for semantic understanding of visual media such as images and videos. Recently, a new type of labeling mechanism known as hash-tags have become increasingly popular on social media sites. In this paper, we study the problem of generating relevant and useful hash-tags for short video clips. Traditional data-driven approaches for tag enrichment and recommendation use direct visual similarity for label transfer and propagation. We attempt to learn a direct low-cost mapping from video to hash-tags using a two step training process. We first employ a natural language processing (NLP) technique, skip-gram models with neural network training to learn a low-dimensional vector representation of hash-tags (Tag2Vec) using a corpus of 10 million hash-tags. We then train an embedding function to map video features to the low-dimensional Tag2vec space. We learn this embedding for 29 categories of short video clips with hash-tags. A query video without any tag-information can then be directly mapped to the vector space of tags using the learned embedding and relevant tags can be found by performing a simple nearest-neighbor retrieval in the Tag2Vec space. We validate the relevance of the tags suggested by our system qualitatively and quantitatively with a user study.

##### Abstract (translated by Google)
用户给定的标签或标签是用于语义理解视觉媒体（如图像和视频）的宝贵资源。最近，一种称为散列标签的新型标签机制在社交媒体网站上越来越流行。在本文中，我们研究了为短视频片段生成相关和有用的哈希标签的问题。传统的数据驱动的标签丰富和推荐方法使用标签传输和传播的直接视觉相似性。我们试图通过两步训练过程学习从视频到散列标签的直接低成本映射。我们首先使用自然语言处理（NLP）技术，使用神经网络训练的跳跃模型来学习哈希标签（Tag2Vec）的低维矢量表示，其使用1000万个哈希标签的语料库。然后，我们训练嵌入函数将视频特征映射到低维的Tag2vec空间。我们通过散列标签了解29种短视频片段的嵌入。没有任何标签信息的查询视频然后可以使用学习的嵌入直接映射到标签的向量空间，并且可以通过在Tag2Vec空间中执行简单的最近邻居检索来找到相关的标签。我们通过用户研究来定性和定量地验证我们系统建议的标签的相关性。

##### URL
[https://arxiv.org/abs/1612.04061](https://arxiv.org/abs/1612.04061)

##### PDF
[https://arxiv.org/pdf/1612.04061](https://arxiv.org/pdf/1612.04061)

