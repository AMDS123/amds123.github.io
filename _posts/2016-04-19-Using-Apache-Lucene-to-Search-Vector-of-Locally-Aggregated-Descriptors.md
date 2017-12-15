---
layout: post
title: "Using Apache Lucene to Search Vector of Locally Aggregated Descriptors"
date: 2016-04-19 14:08:34
categories: arXiv_CV
tags: arXiv_CV
author: Giuseppe Amato, Paolo Bolettieri, Fabrizio Falchi, Claudio Gennaro, Lucia Vadicamo
mathjax: true
---

* content
{:toc}

##### Abstract
Surrogate Text Representation (STR) is a profitable solution to efficient similarity search on metric space using conventional text search engines, such as Apache Lucene. This technique is based on comparing the permutations of some reference objects in place of the original metric distance. However, the Achilles heel of STR approach is the need to reorder the result set of the search according to the metric distance. This forces to use a support database to store the original objects, which requires efficient random I/O on a fast secondary memory (such as flash-based storages). In this paper, we propose to extend the Surrogate Text Representation to specifically address a class of visual metric objects known as Vector of Locally Aggregated Descriptors (VLAD). This approach is based on representing the individual sub-vectors forming the VLAD vector with the STR, providing a finer representation of the vector and enabling us to get rid of the reordering phase. The experiments on a publicly available dataset show that the extended STR outperforms the baseline STR achieving satisfactory performance near to the one obtained with the original VLAD vectors.

##### Abstract (translated by Google)
代理文本表示（STR）是使用传统文本搜索引擎（如Apache Lucene）在度量空间上进行高效相似搜索的有效方法。这种技术是基于比较一些参考对象的置换来代替原始的度量距离。然而，STR方法的致命弱点是需要根据度量距离重新排列搜索结果集。这迫使使用支持数据库来存储原始对象，这需要在快速辅助存储器（如基于闪存的存储器）上进行高效的随机I / O。在本文中，我们建议扩展代理文本表示来专门处理一类称为本地聚合描述符向量（VLAD）的可视化度量对象。这种方法是基于用STR来表示形成VLAD矢量的各个子矢量，提供矢量的更精细的表示并使我们能够摆脱重新排序阶段。在公开可用的数据集上进行的实验表明，扩展的STR优于基线STR，获得了接近使用原始VLAD载体获得的令人满意的性能。

##### URL
[https://arxiv.org/abs/1604.05576](https://arxiv.org/abs/1604.05576)

##### PDF
[https://arxiv.org/pdf/1604.05576](https://arxiv.org/pdf/1604.05576)

