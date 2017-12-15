---
layout: post
title: "Network-Efficient Distributed Word2vec Training System for Large Vocabularies"
date: 2016-06-27 22:00:21
categories: arXiv_CL
tags: arXiv_CL Language_Model Relation
author: Erik Ordentlich, Lee Yang, Andy Feng, Peter Cnudde, Mihajlo Grbovic, Nemanja Djuric, Vladan Radosavljevic, Gavin Owens
mathjax: true
---

* content
{:toc}

##### Abstract
Word2vec is a popular family of algorithms for unsupervised training of dense vector representations of words on large text corpuses. The resulting vectors have been shown to capture semantic relationships among their corresponding words, and have shown promise in reducing a number of natural language processing (NLP) tasks to mathematical operations on these vectors. While heretofore applications of word2vec have centered around vocabularies with a few million words, wherein the vocabulary is the set of words for which vectors are simultaneously trained, novel applications are emerging in areas outside of NLP with vocabularies comprising several 100 million words. Existing word2vec training systems are impractical for training such large vocabularies as they either require that the vectors of all vocabulary words be stored in the memory of a single server or suffer unacceptable training latency due to massive network data transfer. In this paper, we present a novel distributed, parallel training system that enables unprecedented practical training of vectors for vocabularies with several 100 million words on a shared cluster of commodity servers, using far less network traffic than the existing solutions. We evaluate the proposed system on a benchmark dataset, showing that the quality of vectors does not degrade relative to non-distributed training. Finally, for several quarters, the system has been deployed for the purpose of matching queries to ads in Gemini, the sponsored search advertising platform at Yahoo, resulting in significant improvement of business metrics.

##### Abstract (translated by Google)
Word2vec是在大型文本语料库上进行无监督训练的密集向量表示算法的流行家族。所得到的向量已经被证明可以捕获它们相应的单词之间的语义关系，并且已经显示出将一些自然语言处理（NLP）任务减少到在这些向量上进行数学运算的希望。虽然迄今为止word2vec的应用已经集中在几百万个单词的词汇表中，其中词汇表是同时训练向量的单词的集合，但是新颖的应用正在NLP之外的区域中出现，其中包含数亿个单词的词汇表。现有的word2vec训练系统对于训练如此庞大的词汇表是不切实际的，因为它们要求将所有词汇词汇的载体存储在单个服务器的存储器中，或者由于大规模的网络数据传输而遭受不可接受的训练等待时间。在本文中，我们提出了一种新型的分布式并行训练系统，能够在共享的商品服务器集群上为几百万字的词汇表提供前所未有的矢量实际训练，使用比现有解决方案少得多的网络流量。我们在基准数据集上评估所提出的系统，显示相对于非分布式训练，矢量的质量不降低。最后，几个季度，该系统已被部署用于匹配雅虎赞助的搜索广告平台 - 双子座（Gemini）的广告查询，从而显着改善了商业指标。

##### URL
[https://arxiv.org/abs/1606.08495](https://arxiv.org/abs/1606.08495)

##### PDF
[https://arxiv.org/pdf/1606.08495](https://arxiv.org/pdf/1606.08495)

