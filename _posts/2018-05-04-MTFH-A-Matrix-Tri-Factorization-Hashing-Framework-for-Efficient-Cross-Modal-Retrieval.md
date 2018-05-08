---
layout: post
title: "MTFH: A Matrix Tri-Factorization Hashing Framework for Efficient Cross-Modal Retrieval"
date: 2018-05-04 23:21:15
categories: arXiv_CV
tags: arXiv_CV Relation
author: Xin Liu, Zhikai Hu, Haibin Ling, Yiu-ming Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing has recently sparked a great revolution in cross-modal retrieval due to its low storage cost and high query speed. Most existing cross-modal hashing methods learn unified hash codes in a common Hamming space to represent all multi-modal data and make them intuitively comparable. However, such unified hash codes could inherently sacrifice their representation scalability because the data from different modalities may not have one-to-one correspondence and could be stored more efficiently by different hash codes of unequal lengths. To mitigate this problem, this paper proposes a generalized and flexible cross-modal hashing framework, termed Matrix Tri-Factorization Hashing (MTFH), which not only preserves the semantic similarity between the multi-modal data points, but also works seamlessly in various settings including paired or unpaired multi-modal data, and equal or varying hash length encoding scenarios. Specifically, MTFH exploits an efficient objective function to jointly learn the flexible modality-specific hash codes with different length settings, while simultaneously excavating two semantic correlation matrices to ensure heterogeneous data comparable. As a result, the derived hash codes are more semantically meaningful for various challenging cross-modal retrieval tasks. Extensive experiments evaluated on public benchmark datasets highlight the superiority of MTFH under various retrieval scenarios and show its very competitive performance with the state-of-the-arts.

##### Abstract (translated by Google)
由于存储成本低，查询速度快，哈希最近引发了跨模式检索方面的巨大革命。大多数现有的交叉模式散列方法在统一的汉明空间中学习统一的散列码，以表示所有多模态数据，并使其直观可比。然而，这种统一的散列码可能会固有地牺牲它们的表示可缩放性，因为来自不同模态的数据可能不具有一一对应关系，并且可能被不同长度的不同散列码更有效地存储。为了缓解这个问题，本文提出了一个广义而灵活的跨模态哈希框架，称为矩阵三因子分解哈希（MTFH），它不仅保留了多模态数据点之间的语义相似性，而且还可以在各种设置中无缝地工作包括配对或不配对的多模式数据，以及相等或不同的哈希长度编码方案。具体而言，MTFH利用高效的目标函数共同学习具有不同长度设置的灵活模态特定哈希码，同时挖掘两个语义相关矩阵以确保异类数据的可比性。因此，对于各种具有挑战性的跨模式检索任务而言，派生的散列码在语义上更有意义。在公共基准数据集上评估的大量实验突出了MTFH在各种检索情景下的优越性，并展示了其与艺术级别的非常具有竞争力的表现。

##### URL
[http://arxiv.org/abs/1805.01963](http://arxiv.org/abs/1805.01963)

##### PDF
[http://arxiv.org/pdf/1805.01963](http://arxiv.org/pdf/1805.01963)

