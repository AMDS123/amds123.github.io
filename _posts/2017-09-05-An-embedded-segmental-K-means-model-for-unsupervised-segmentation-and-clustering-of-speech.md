---
layout: post
title: "An embedded segmental K-means model for unsupervised segmentation and clustering of speech"
date: 2017-09-05 14:14:11
categories: arXiv_SD
tags: arXiv_SD Segmentation Embedding Inference
author: Herman Kamper, Karen Livescu, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised segmentation and clustering of unlabelled speech are core problems in zero-resource speech processing. Most approaches lie at methodological extremes: some use probabilistic Bayesian models with convergence guarantees, while others opt for more efficient heuristic techniques. Despite competitive performance in previous work, the full Bayesian approach is difficult to scale to large speech corpora. We introduce an approximation to a recent Bayesian model that still has a clear objective function but improves efficiency by using hard clustering and segmentation rather than full Bayesian inference. Like its Bayesian counterpart, this embedded segmental K-means model (ES-KMeans) represents arbitrary-length word segments as fixed-dimensional acoustic word embeddings. We first compare ES-KMeans to previous approaches on common English and Xitsonga data sets (5 and 2.5 hours of speech): ES-KMeans outperforms a leading heuristic method in word segmentation, giving similar scores to the Bayesian model while being 5 times faster with fewer hyperparameters. However, its clusters are less pure than those of the other models. We then show that ES-KMeans scales to larger corpora by applying it to the 5 languages of the Zero Resource Speech Challenge 2017 (up to 45 hours), where it performs competitively compared to the challenge baseline.

##### Abstract (translated by Google)
无监督分词和未标记语音的聚类是零资源语音处理中的核心问题。大多数方法都在方法论极端：一些使用具有收敛保证的概率贝叶斯模型，而另一些则选择更有效的启发式技术。尽管在以前的工作中有出色的表现，但是完整的贝叶斯方法难以扩展到大型的语言语料库。我们引入近似贝叶斯模型，它仍然有一个明确的目标函数，但通过使用硬聚类和分割而不是完全贝叶斯推断来提高效率。像其贝叶斯对应，这种嵌入式分段K均值模型（ES-KMeans）将任意长度的分段表示为固定维声学嵌入。我们首先比较ES-KMeans和普通英语和Xitsonga数据集（5小时和2.5小时的语言）之前的方法：ES-KMeans在分词方面优于领先的启发式方法，与贝叶斯模型相比得分相似，更少的超参数。但是，其集群不如其他模型那么纯粹。然后我们证明，通过将ES-KMeans应用于2017年零资源演讲挑战赛的5种语言（长达45小时），ES-KMeans可以扩展到较大的语料库，与挑战基线相比，它具有竞争力。

##### URL
[https://arxiv.org/abs/1703.08135](https://arxiv.org/abs/1703.08135)

##### PDF
[https://arxiv.org/pdf/1703.08135](https://arxiv.org/pdf/1703.08135)

