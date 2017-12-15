---
layout: post
title: "GaKCo: a Fast GApped k-mer string Kernel using COunting"
date: 2017-09-18 17:25:17
categories: arXiv_CL
tags: arXiv_CL
author: Ritambhara Singh, Arshdeep Sekhon, Kamran Kowsari, Jack Lanchantin, Beilun Wang, Yanjun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
String Kernel (SK) techniques, especially those using gapped $k$-mers as features (gk), have obtained great success in classifying sequences like DNA, protein, and text. However, the state-of-the-art gk-SK runs extremely slow when we increase the dictionary size ($\Sigma$) or allow more mismatches ($M$). This is because current gk-SK uses a trie-based algorithm to calculate co-occurrence of mismatched substrings resulting in a time cost proportional to $O(\Sigma^{M})$. We propose a \textbf{fast} algorithm for calculating \underline{Ga}pped $k$-mer \underline{K}ernel using \underline{Co}unting (GaKCo). GaKCo uses associative arrays to calculate the co-occurrence of substrings using cumulative counting. This algorithm is fast, scalable to larger $\Sigma$ and $M$, and naturally parallelizable. We provide a rigorous asymptotic analysis that compares GaKCo with the state-of-the-art gk-SK. Theoretically, the time cost of GaKCo is independent of the $\Sigma^{M}$ term that slows down the trie-based approach. Experimentally, we observe that GaKCo achieves the same accuracy as the state-of-the-art and outperforms its speed by factors of 2, 100, and 4, on classifying sequences of DNA (5 datasets), protein (12 datasets), and character-based English text (2 datasets), respectively. GaKCo is shared as an open source tool at \url{this https URL}

##### Abstract (translated by Google)
字符串内核（SK）技术，尤其是那些使用缺口$ k $ -mer作为特征（gk）的技术，在分类DNA，蛋白质和文本等序列方面取得了巨大的成功。然而，当我们增加字典大小（$ \ Sigma $）或者允许更多的不匹配（$ M $）时，最先进的gk-SK运行非常缓慢。这是因为当前的gk-SK使用基于树的算法来计算不匹配的子串的共现，导致时间成本与$ O（\ Sigma ^ {M}）$成比例。我们提出了一个\ textbf {fast}算法来计算\ underline {Ga} pped $ k $ -mer \ underline {K} ernel using \ underline {Co} unting（GaKCo）。 GaKCo使用关联数组来计算使用累积计数的子字符串的同时出现。这个算法是快速的，可扩展到更大的$ \ Sigma $和$ M $，并且自然可并行化。我们提供了一个严格的渐近分析，比较GaKCo和最先进的gk-SK。从理论上讲，GaKCo的时间成本与$ \ Sigma ^ {M} $术语无关，这减慢了基于特征值的方法。在实验中，我们观察到，GaKCo达到了与现有技术相同的精确度，并且在分类DNA（5个数据集），蛋白质（12个数据集）的序列方面超过了2,100和4倍的速度，基于字符的英文文本（2个数据集）。 GaKCo在\ url {this https URL}中作为开源工具共享

##### URL
[https://arxiv.org/abs/1704.07468](https://arxiv.org/abs/1704.07468)

##### PDF
[https://arxiv.org/pdf/1704.07468](https://arxiv.org/pdf/1704.07468)

