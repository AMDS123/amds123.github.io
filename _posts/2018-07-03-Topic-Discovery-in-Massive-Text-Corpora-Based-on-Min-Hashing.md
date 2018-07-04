---
layout: post
title: "Topic Discovery in Massive Text Corpora Based on Min-Hashing"
date: 2018-07-03 00:52:50
categories: arXiv_CL
tags: arXiv_CL Quantitative
author: Gibran Fuentes-Pineda, Ivan Vladimir Meza-Ruiz
mathjax: true
---

* content
{:toc}

##### Abstract
The task of discovering topics in text corpora has been dominated by Latent Dirichlet Allocation and other Topic Models for over a decade. In order to apply these approaches to massive text corpora, the vocabulary needs to be reduced considerably and large computer clusters and/or GPUs are typically required. Moreover, the number of topics must be provided beforehand but this depends on the corpus characteristics and it is often difficult to estimate, especially for massive text corpora. Unfortunately, both topic quality and time complexity are sensitive to this choice. This paper describes an alternative approach to discover topics based on Min-Hashing, which can handle massive text corpora and large vocabularies using modest computer hardware and does not require to fix the number of topics in advance. The basic idea is to generate multiple random partitions of the corpus vocabulary to find sets of highly co-occurring words, which are then clustered to produce the final topics. In contrast to probabilistic topic models where topics are distributions over the complete vocabulary, the topics discovered by the proposed approach are sets of highly co-occurring words. Interestingly, these topics underlie various thematics with different levels of granularity. An extensive qualitative and quantitative evaluation using the 20 Newsgroups (18K), Reuters (800K), Spanish Wikipedia (1M), and English Wikipedia (5M) corpora shows that the proposed approach is able to consistently discover meaningful and coherent topics. Remarkably, the time complexity of the proposed approach is linear with respect to corpus and vocabulary size; a non-parallel implementation was able to discover topics from the entire English edition of Wikipedia with over 5 million documents and 1 million words in less than 7 hours.

##### Abstract (translated by Google)
十多年来，在潜在的Dirichlet分配和其他主题模型中，发现文本语料库中的主题的任务一直占主导地位。为了将这些方法应用于大规模文本语料库，需要大大减少词汇量，并且通常需要大型计算机集群和/或GPU。此外，必须预先提供主题的数量，但这取决于语料库特征，并且通常很难估计，特别是对于大量文本语料库。不幸的是，主题质量和时间复杂性都对这种选择很敏感。本文描述了一种基于Min-Hashing发现主题的替代方法，Min-Hashing可以使用适度的计算机硬件处理大量文本语料库和大型词汇表，并且不需要提前修复主题数量。基本思想是生成语料库词汇表的多个随机分区以找到高度共同发生的单词集合，然后将其聚类以产生最终主题。与主题是完整词汇表的分布的概率主题模型相比，所提出的方法发现的主题是高度共同发生的词组。有趣的是，这些主题是具有不同粒度级别的各种主题的基础。使用20个新闻组（18K），路透社（800K），西班牙语维基百科（1M）和英语维基百科（5M）语料库进行广泛的定性和定量评估表明，所提出的方法能够始终如一地发现有意义且连贯的主题。值得注意的是，所提方法的时间复杂度在语料库和词汇量方面是线性的;一个非并行的实现能够在不到7个小时的时间内发现整个英文版维基百科的主题，包含500多万个文档和100万个单词。

##### URL
[https://arxiv.org/abs/1807.00938](https://arxiv.org/abs/1807.00938)

##### PDF
[https://arxiv.org/pdf/1807.00938](https://arxiv.org/pdf/1807.00938)

