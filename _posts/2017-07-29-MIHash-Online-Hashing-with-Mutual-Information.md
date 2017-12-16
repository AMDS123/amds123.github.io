---
layout: post
title: "MIHash: Online Hashing with Mutual Information"
date: 2017-07-29 23:09:59
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Gradient_Descent
author: Fatih Cakir, Kun He, Sarah Adel Bargal, Stan Sclaroff
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based hashing methods are widely used for nearest neighbor retrieval, and recently, online hashing methods have demonstrated good performance-complexity trade-offs by learning hash functions from streaming data. In this paper, we first address a key challenge for online hashing: the binary codes for indexed data must be recomputed to keep pace with updates to the hash functions. We propose an efficient quality measure for hash functions, based on an information-theoretic quantity, mutual information, and use it successfully as a criterion to eliminate unnecessary hash table updates. Next, we also show how to optimize the mutual information objective using stochastic gradient descent. We thus develop a novel hashing method, MIHash, that can be used in both online and batch settings. Experiments on image retrieval benchmarks (including a 2.5M image dataset) confirm the effectiveness of our formulation, both in reducing hash table recomputations and in learning high-quality hash functions.

##### Abstract (translated by Google)
基于学习的散列方法被广泛用于最近邻居检索，最近，在线散列方法通过从流数据中学习散列函数展示了良好的性能 - 复杂度折衷。在本文中，我们首先解决在线散列的关键挑战：索引数据的二进制代码必须重新计算以跟上散列函数的更新步伐。我们基于信息理论的数量，互信息，提出了一种有效的散列函数质量度量方法，并成功地将其用作一个标准来消除不必要的散列表更新。接下来，我们还展示了如何使用随机梯度下降来优化互信息目标。因此，我们开发了一种新的哈希方法MIHash，可以在线和批处理设置中使用。图像检索基准（包括一个2.5M的图像数据集）的实验证实了我们的公式的有效性，无论是减少哈希表重新计算和学习高品质的哈希函数。

##### URL
[https://arxiv.org/abs/1703.08919](https://arxiv.org/abs/1703.08919)

##### PDF
[https://arxiv.org/pdf/1703.08919](https://arxiv.org/pdf/1703.08919)

