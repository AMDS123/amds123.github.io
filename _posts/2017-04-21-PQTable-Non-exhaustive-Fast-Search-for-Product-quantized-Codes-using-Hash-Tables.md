---
layout: post
title: "PQTable: Non-exhaustive Fast Search for Product-quantized Codes using Hash Tables"
date: 2017-04-21 14:22:16
categories: arXiv_CV
tags: arXiv_CV
author: Yusuke Matsui, Toshihiko Yamasaki, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a product quantization table (PQTable); a fast search method for product-quantized codes via hash-tables. An identifier of each database vector is associated with the slot of a hash table by using its PQ-code as a key. For querying, an input vector is PQ-encoded and hashed, and the items associated with that code are then retrieved. The proposed PQTable produces the same results as a linear PQ scan, and is 10^2 to 10^5 times faster. Although state-of-the-art performance can be achieved by previous inverted-indexing-based approaches, such methods require manually-designed parameter setting and significant training; our PQTable is free of these limitations, and therefore offers a practical and effective solution for real-world problems. Specifically, when the vectors are highly compressed, our PQTable achieves one of the fastest search performances on a single CPU to date with significantly efficient memory usage (0.059 ms per query over 10^9 data points with just 5.5 GB memory consumption). Finally, we show that our proposed PQTable can naturally handle the codes of an optimized product quantization (OPQTable).

##### Abstract (translated by Google)
在本文中，我们提出一个产品量化表（PQTable）;产品量化代码的快速搜索方法通过哈希表。每个数据库向量的标识符通过使用其PQ代码作为关键字与散列表的槽相关联。对于查询，输入向量是PQ编码和散列，然后检索与该代码相关的项目。所提出的PQTable产生与线性PQ扫描相同的结果，并且快10 ^ 2到10 ^ 5倍。尽管先前的倒排索引方法可以实现最先进的性能，但这种方法需要手动设计的参数设置和重要的训练;我们的PQTable没有这些限制，因此为现实世界的问题提供了一个切实有效的解决方案。具体而言，当向量被高度压缩时，我们的PQTable在单个CPU上实现了迄今为止最快的搜索性能之一，并具有显着高效的内存使用率（仅在5.5 GB内存消耗下，每个查询超过10 ^ 9个数据点，每个查询为0.059 ms）。最后，我们表明，我们提出的PQTable可以自然地处理优化产品量化（OPQTable）的代码。

##### URL
[https://arxiv.org/abs/1704.06556](https://arxiv.org/abs/1704.06556)

##### PDF
[https://arxiv.org/pdf/1704.06556](https://arxiv.org/pdf/1704.06556)

