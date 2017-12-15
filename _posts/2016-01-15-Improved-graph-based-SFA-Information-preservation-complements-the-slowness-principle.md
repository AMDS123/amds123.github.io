---
layout: post
title: "Improved graph-based SFA: Information preservation complements the slowness principle"
date: 2016-01-15 15:00:20
categories: arXiv_CV
tags: arXiv_CV Classification
author: Alberto N. Escalante-B., Laurenz Wiskott
mathjax: true
---

* content
{:toc}

##### Abstract
Slow feature analysis (SFA) is an unsupervised-learning algorithm that extracts slowly varying features from a multi-dimensional time series. A supervised extension to SFA for classification and regression is graph-based SFA (GSFA). GSFA is based on the preservation of similarities, which are specified by a graph structure derived from the labels. It has been shown that hierarchical GSFA (HGSFA) allows learning from images and other high-dimensional data. The feature space spanned by HGSFA is complex due to the composition of the nonlinearities of the nodes in the network. However, we show that the network discards useful information prematurely before it reaches higher nodes, resulting in suboptimal global slowness and an under-exploited feature space. To counteract these problems, we propose an extension called hierarchical information-preserving GSFA (HiGSFA), where information preservation complements the slowness-maximization goal. We build a 10-layer HiGSFA network to estimate human age from facial photographs of the MORPH-II database, achieving a mean absolute error of 3.50 years, improving the state-of-the-art performance. HiGSFA and HGSFA support multiple-labels and offer a rich feature space, feed-forward training, and linear complexity in the number of samples and dimensions. Furthermore, HiGSFA outperforms HGSFA in terms of feature slowness, estimation accuracy and input reconstruction, giving rise to a promising hierarchical supervised-learning approach.

##### Abstract (translated by Google)
慢特征分析（SFA）是一种无监督学习算法，可从多维时间序列中提取缓慢变化的特征。对SFA进行分类和回归的监督扩展是基于图形的SFA（GSFA）。 GSFA是基于相似性的保存，这些相似性由从标签导出的图结构指定。已经表明，等级GSFA（HGSFA）允许从图像和其他高维数据中学习。由于网络中节点的非线性组成，HGSFA所跨越的特征空间是复杂的。然而，我们表明，网络在到达更高的节点之前过早丢弃有用的信息，导致全局缓慢和特征空间不足。为了解决这些问题，我们提出了一种称为分层信息保存的GSFA（HiGSFA）的扩展，其中信息保存是对缓慢最大化目标的补充。我们建立了10层HiGSFA网络，从MORPH-II数据库的面部照片估计人类年龄，实现了3.50年的平均绝对误差，改善了最新的性能。 HiGSFA和HGSFA支持多标签，并提供丰富的特征空间，前馈训练和样本数量和维度的线性复杂度。此外，在特征缓慢度，估计精度和输入重建方面，HiGSFA优于HGSFA，从而产生了有前途的分级监督学习方法。

##### URL
[https://arxiv.org/abs/1601.03945](https://arxiv.org/abs/1601.03945)

##### PDF
[https://arxiv.org/pdf/1601.03945](https://arxiv.org/pdf/1601.03945)

