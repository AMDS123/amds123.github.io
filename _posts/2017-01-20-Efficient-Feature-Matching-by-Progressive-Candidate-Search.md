---
layout: post
title: "Efficient Feature Matching by Progressive Candidate Search"
date: 2017-01-20 03:52:48
categories: arXiv_CV
tags: arXiv_CV
author: Sehyung Lee, Jongwoo Lim, Il Hong Suh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel feature matching algorithm that systematically utilizes the geometric properties of features such as position, scale, and orientation, in addition to the conventional descriptor vectors. In challenging scenes with the presence of repetitive patterns or with a large viewpoint change, it is hard to find the correct correspondences using feature descriptors only, since the descriptor distances of the correct matches may not be the least among the candidates due to appearance changes. Assuming that the layout of the nearby features does not changed much, we propose the bidirectional transfer measure to gauge the geometric consistency of a pair of feature correspondences. The feature matching problem is formulated as a Markov random field (MRF) which uses descriptor distances and relative geometric similarities together. The unmatched features are explicitly modeled in the MRF to minimize its negative impact. For speed and stability, instead of solving the MRF on the entire features at once, we start with a small set of confident feature matches, and then progressively search the candidates in nearby features and expand the MRF with them. Experimental comparisons show that the proposed algorithm finds better feature correspondences, i.e. more matches with higher inlier ratio, in many challenging scenes with much lower computational cost than the state-of-the-art algorithms.

##### Abstract (translated by Google)
除了传统的描述符向量之外，我们还提出了一种新颖的特征匹配算法，系统地利用位置，比例和方向等特征的几何属性。在具有重复模式或大视点变化的具有挑战性的场景中，很难仅使用特征描述符来找到正确的对应关系，因为由于外观变化，正确匹配的描述符距离可能不是最小的。假设附近特征的布局没有太大改变，我们提出双向转移测量来衡量一对特征对应的几何一致性。特征匹配问题被表述为马尔科夫随机场（MRF），其使用描述符距离和相对几何相似性。无可比拟的特性在MRF中被明确地建模，以尽量减少其负面影响。为了速度和稳定性，我们不是一次解决整个特征的MRF，而是从一小组自信的特征匹配开始，然后逐步搜索附近特征的候选者，并扩展MRF。实验比较表明，所提出的算法在许多具有挑战性的场景中找到更好的特征对应关系，即具有更高的内点比率的更多匹配，比现有技术算法具有低得多的计算成本。

##### URL
[https://arxiv.org/abs/1701.05676](https://arxiv.org/abs/1701.05676)

##### PDF
[https://arxiv.org/pdf/1701.05676](https://arxiv.org/pdf/1701.05676)

