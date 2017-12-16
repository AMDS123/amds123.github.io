---
layout: post
title: "A Revisit on Deep Hashings for Large-scale Content Based Image Retrieval"
date: 2017-11-16 10:45:39
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN
author: Deng Cai, Xiuye Gu, Chaoqi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
There is a growing trend in studying deep hashing methods for content-based image retrieval (CBIR), where hash functions and binary codes are learnt using deep convolutional neural networks and then the binary codes can be used to do approximate nearest neighbor (ANN) search. All the existing deep hashing papers report their methods' superior performance over the traditional hashing methods according to their experimental results. However, there are serious flaws in the evaluations of existing deep hashing papers: (1) The datasets they used are too small and simple to simulate the real CBIR situation. (2) They did not correctly include the search time in their evaluation criteria, while the search time is crucial in real CBIR systems. (3) The performance of some unsupervised hashing algorithms (e.g., LSH) can easily be boosted if one uses multiple hash tables, which is an important factor should be considered in the evaluation while most of the deep hashing papers failed to do so. We re-evaluate several state-of-the-art deep hashing methods with a carefully designed experimental setting. Empirical results reveal that the performance of these deep hashing methods are inferior to multi-table IsoH, a very simple unsupervised hashing method. Thus, the conclusions in all the deep hashing papers should be carefully re-examined.

##### Abstract (translated by Google)
在基于内容的图像检索（CBIR）的深度哈希方法研究中，使用深度卷积神经网络学习哈希函数和二进制代码，然后可以使用二进制代码进行近似最近邻（ANN）搜索。所有现有的深度散列论文都根据他们的实验结果报告了他们的方法比传统的散列方法更优越的性能。然而，现有深度散列论文评价存在严重缺陷：（1）他们使用的数据集太小，很难模拟真实的CBIR情况。 （2）他们没有把搜索时间正确地包括在他们的评估标准中，而搜索时间在真正的CBIR系统中是至关重要的。 （3）如果使用多个哈希表，那么一些无监督哈希算法（例如LSH）的性能可以很容易地提高，这是评估中应该考虑的一个重要因素，而大多数深度哈希算法都没有这样做。我们用精心设计的实验环境重新评估了几种最先进的深度哈希方法。实验结果表明，这些深度哈希方法的性能不如多表IsoH，这是一个非常简单的无监督哈希方法。因此，所有深度哈希文件中的结论都应仔细重新审视。

##### URL
[https://arxiv.org/abs/1711.06016](https://arxiv.org/abs/1711.06016)

##### PDF
[https://arxiv.org/pdf/1711.06016](https://arxiv.org/pdf/1711.06016)

