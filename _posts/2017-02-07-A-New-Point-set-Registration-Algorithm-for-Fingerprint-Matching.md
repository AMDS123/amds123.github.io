---
layout: post
title: "A New Point-set Registration Algorithm for Fingerprint Matching"
date: 2017-02-07 03:43:31
categories: arXiv_CV
tags: arXiv_CV
author: A. Pasha Hosseinbor, Renat Zhdanov, Alexander Ushveridze
mathjax: true
---

* content
{:toc}

##### Abstract
A novel minutia-based fingerprint matching algorithm is proposed that employs iterative global alignment on two minutia sets. The matcher considers all possible minutia pairings and iteratively aligns the two sets until the number of minutia pairs does not exceed the maximum number of allowable one-to-one pairings. The optimal alignment parameters are derived analytically via linear least squares. The first alignment establishes a region of overlap between the two minutia sets, which is then (iteratively) refined by each successive alignment. After each alignment, minutia pairs that exhibit weak correspondence are discarded. The process is repeated until the number of remaining pairs no longer exceeds the maximum number of allowable one-to-one pairings. The proposed algorithm is tested on both the FVC2000 and FVC2002 databases, and the results indicate that the proposed matcher is both effective and efficient for fingerprint authentication; it is fast and does not utilize any computationally expensive mathematical functions (e.g. trigonometric, exponential). In addition to the proposed matcher, another contribution of the paper is the analytical derivation of the least squares solution for the optimal alignment parameters for two point-sets lacking exact correspondence.

##### Abstract (translated by Google)
提出一种新的基于细节点的指纹匹配算法，该算法采用迭代全局比对两个细节集。匹配器考虑所有可能的细节配对并且迭代地对齐两个集合，直到细节对的数量不超过允许的一对一配对的最大数量。通过线性最小二乘法分析导出最佳对准参数。第一个对齐建立了两个细节集之间的重叠区域，然后每个连续对齐（迭代）对其进行细化。在每次对齐之后，丢弃展现弱对应的细节对。重复该过程，直到剩余对的数量不再超过可允许的一对一配对的最大数量。该算法在FVC2000和FVC2002数据库上都进行了测试，结果表明所提出的匹配器对于指纹认证是有效和高效的;它速度快并且不利用任何计算上昂贵的数学函数（例如三角函数，指数函数）。除了所提出的匹配器之外，本文的另一个贡献是针对缺乏精确对应的两个点集的最佳对准参数的最小二乘解的分析推导。

##### URL
[https://arxiv.org/abs/1702.01870](https://arxiv.org/abs/1702.01870)

##### PDF
[https://arxiv.org/pdf/1702.01870](https://arxiv.org/pdf/1702.01870)

