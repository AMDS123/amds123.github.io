---
layout: post
title: "Efficient end-to-end learning for quantizable representations"
date: 2018-05-15 14:32:31
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding Represenation_Learning
author: Yeonwoo Jeong, Hyun Oh Song
mathjax: true
---

* content
{:toc}

##### Abstract
Embedding representation learning via neural networks is at the core foundation of modern similarity based search. While much effort has been put in developing algorithms for learning binary hamming code representations for search efficiency, this still requires a linear scan of the entire dataset per each query and trades off the search accuracy through binarization. To this end, we consider the problem of directly learning a quantizable embedding representation and the sparse binary hash code end-to-end which can be used to construct an efficient hash table not only providing significant search reduction in the number of data but also achieving the state of the art search accuracy outperforming previous state of the art deep metric learning methods. We also show that finding the optimal sparse binary hash code in a mini-batch can be computed exactly in polynomial time by solving a minimum cost flow problem. Our results on Cifar-100 and on ImageNet datasets show the state of the art search accuracy in precision@k and NMI metrics while providing up to 98X and 478X search speedup respectively over exhaustive linear search.

##### Abstract (translated by Google)
通过神经网络嵌入表示学习是现代相似性搜索的核心基础。尽管为了提高搜索效率而开发用于学习二进制汉明码表示的算法已经付出了很多努力，但是这仍然需要对每个查询的整个数据集进行线性扫描并且通过二值化将搜索精度折衷。为此，我们考虑直接学习可量化嵌入表示和端到端稀疏二进制散列码的问题，其可以用于构造高效散列表，不仅提供显着的数据数量搜索减少，而且实现现有技术的搜索准确性优于先前的现有技术深度量度学习方法。我们还表明，通过求解最小代价流问题，可以在多项式时间内精确计算最小稀疏二进制散列码。我们在Cifar-100和ImageNet数据集上的结果显示了精度@ k和NMI指标的最新搜索精度状态，同时通过彻底的线性搜索分别提供高达98X和478X的搜索加速。

##### URL
[http://arxiv.org/abs/1805.05809](http://arxiv.org/abs/1805.05809)

##### PDF
[http://arxiv.org/pdf/1805.05809](http://arxiv.org/pdf/1805.05809)

