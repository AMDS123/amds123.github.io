---
layout: post
title: "Revisiting the Inverted Indices for Billion-Scale Approximate Nearest Neighbors"
date: 2018-02-07 14:01:04
categories: arXiv_CV
tags: arXiv_CV
author: Dmitry Baranchuk, Artem Babenko, Yury Malkov
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the problem of billion-scale nearest neighbor search. The state-of-the-art retrieval systems for billion-scale databases are currently based on the inverted multi-index, the recently proposed generalization of the inverted index structure. The multi-index provides a very fine-grained partition of the feature space that allows extracting concise and accurate short-lists of candidates for the search queries. In this paper, we argue that the potential of the simple inverted index was not fully exploited in previous works and advocate its usage both for the highly-entangled deep descriptors and relatively disentangled SIFT descriptors. We introduce a new retrieval system that is based on the inverted index and outperforms the multi-index by a large margin for the same memory consumption and construction complexity. For example, our system achieves the state-of-the-art recall rates up to six times faster on the dataset of one billion deep descriptors compared to the efficient implementation of the inverted multi-index from the FAISS library.

##### Abstract (translated by Google)
这项工作解决了十亿尺度最近邻搜索的问题。针对十亿级数据库的最先进的检索系统目前基于反向多指数，即最近提出的倒排索引结构的推广。多索引提供了对特征空间的非常细粒度的分割，从而能够为搜索查询提取简明准确的候选短列表。在本文中，我们认为简单倒排索引的潜力在以前的作品中没有被充分利用，并且主张它用于高度纠缠的深描述符和相对松散的SIFT描述符。我们引入了一种新的基于倒排索引的检索系统，在相同的内存消耗和构造复杂度的情况下，大大优于多索引。例如，与从FAISS库中有效实施倒排多指数相比，我们的系统在十亿个深度描述符的数据集上实现了最先进的召回率，速度提高了六倍。

##### URL
[https://arxiv.org/abs/1802.02422](https://arxiv.org/abs/1802.02422)

##### PDF
[https://arxiv.org/pdf/1802.02422](https://arxiv.org/pdf/1802.02422)

