---
layout: post
title: "PQk-means: Billion-scale Clustering for Product-quantized Codes"
date: 2017-09-12 07:00:18
categories: arXiv_CV
tags: arXiv_CV
author: Yusuke Matsui, Keisuke Ogaki, Toshihiko Yamasaki, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
Data clustering is a fundamental operation in data analysis. For handling large-scale data, the standard k-means clustering method is not only slow, but also memory-inefficient. We propose an efficient clustering method for billion-scale feature vectors, called PQk-means. By first compressing input vectors into short product-quantized (PQ) codes, PQk-means achieves fast and memory-efficient clustering, even for high-dimensional vectors. Similar to k-means, PQk-means repeats the assignment and update steps, both of which can be performed in the PQ-code domain. Experimental results show that even short-length (32 bit) PQ-codes can produce competitive results compared with k-means. This result is of practical importance for clustering in memory-restricted environments. Using the proposed PQk-means scheme, the clustering of one billion 128D SIFT features with K = 10^5 is achieved within 14 hours, using just 32 GB of memory consumption on a single computer.

##### Abstract (translated by Google)
数据聚类是数据分析的基本操作。为了处理大规模的数据，标准k-均值聚类方法不仅速度慢，而且存储效率低。我们提出了一个有效的聚类方法，称为PQk-means。通过首先将输入向量压缩成短产品量化（PQ）码，即使对于高维向量，PQk均值也实现了快速且高效的存储聚类。类似于k-means，PQk-means重复分配和更新步骤，这两个步骤都可以在PQ码域中执行。实验结果表明，与k均值相比，即使是短码（32比特）的PQ码也能产生有竞争力的结果。这个结果对于限制内存的环境中的集群是非常重要的。使用所提出的PQk均值方案，在一个计算机上仅需32 GB的内存消耗就可以在14小时内对K = 10 ^ 5的十亿个128D SIFT特征进行聚类。

##### URL
[https://arxiv.org/abs/1709.03708](https://arxiv.org/abs/1709.03708)

##### PDF
[https://arxiv.org/pdf/1709.03708](https://arxiv.org/pdf/1709.03708)

