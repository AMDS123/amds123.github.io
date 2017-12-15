---
layout: post
title: "Stability of Topic Modeling via Matrix Factorization"
date: 2017-09-09 17:06:18
categories: arXiv_SD
tags: arXiv_SD
author: Mark Belford, Brian Mac Namee, Derek Greene
mathjax: true
---

* content
{:toc}

##### Abstract
Topic models can provide us with an insight into the underlying latent structure of a large corpus of documents. A range of methods have been proposed in the literature, including probabilistic topic models and techniques based on matrix factorization. However, in both cases, standard implementations rely on stochastic elements in their initialization phase, which can potentially lead to different results being generated on the same corpus when using the same parameter values. This corresponds to the concept of "instability" which has previously been studied in the context of $k$-means clustering. In many applications of topic modeling, this problem of instability is not considered and topic models are treated as being definitive, even though the results may change considerably if the initialization process is altered. In this paper we demonstrate the inherent instability of popular topic modeling approaches, using a number of new measures to assess stability. To address this issue in the context of matrix factorization for topic modeling, we propose the use of ensemble learning strategies. Based on experiments performed on annotated text corpora, we show that a K-Fold ensemble strategy, combining both ensembles and structured initialization, can significantly reduce instability, while simultaneously yielding more accurate topic models.

##### Abstract (translated by Google)
主题模型可以帮助我们深入了解大量文档的潜在结构。文献中已经提出了一系列方法，包括基于矩阵分解的概率主题模型和技术。但是，在这两种情况下，标准实现都依赖于随机元素的初始化阶段，这可能会导致在使用相同参数值时在同一个语料库上生成不同的结果。这对应于之前在$ k $ -means聚类的背景下研究的“不稳定性”的概念。在主题建模的许多应用中，这个不稳定的问题没有被考虑，主题模型被认为是确定性的，尽管如果初始化过程被改变，结果可能会发生相当大的变化。在本文中，我们展示了流行主题建模方法的固有不稳定性，采用了一些新的措施来评估稳定性。为了在主题建模矩阵分解的背景下解决这个问题，我们提出使用集合学习策略。基于在注释文本语料库上进行的实验，我们证明集合了合奏和结构化初始化的K-fold集合策略可以显着减少不稳定性，同时产生更准确的主题模型。

##### URL
[https://arxiv.org/abs/1702.07186](https://arxiv.org/abs/1702.07186)

##### PDF
[https://arxiv.org/pdf/1702.07186](https://arxiv.org/pdf/1702.07186)

