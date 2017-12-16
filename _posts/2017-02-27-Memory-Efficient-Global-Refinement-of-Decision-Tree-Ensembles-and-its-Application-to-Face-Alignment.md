---
layout: post
title: "Memory-Efficient Global Refinement of Decision-Tree Ensembles and its Application to Face Alignment"
date: 2017-02-27 19:25:53
categories: arXiv_CV
tags: arXiv_CV Face
author: Nenad Markuš, Ivan Gogić, Igor S. Pandžić, Jörgen Ahlberg
mathjax: true
---

* content
{:toc}

##### Abstract
Ren et al. recently introduced a method for aggregating multiple decision trees into a strong predictor by interpreting a path taken by a sample down each tree as a binary vector and performing linear regression on top of these vectors stacked together. They provided experimental evidence that the method offers advantages over the usual approaches for combining decision trees (random forests and boosting). The method truly shines when the regression target is a large vector with correlated dimensions, such as a 2D face shape represented with the positions of several facial landmarks. However, we argue that their basic method is not applicable in many practical scenarios due to large memory requirements. This paper shows how this issue can be solved through the use of quantization and architectural changes of the predictor that maps decision tree-derived encodings to the desired output.

##### Abstract (translated by Google)
Ren等人最近引入了一种方法，将多个决策树聚合成一个强预测器，方法是将每个树下样本所采用的路径解释为一个二进制向量，然后对堆叠在一起的这些向量顶部进行线性回归。他们提供了实验证据表明，这种方法比通常的决策树（随机森林和提升）方法提供了更多的优势。当回归目标是具有相关维度的大向量时，该方法真正地发光，诸如用几个面部标志的位置表示的2D面部形状。然而，我们认为，由于内存需求量大，其基本方法不适用于很多实际场景。本文展示了如何通过使用将决策树派生的编码映射到期望的输出的预测器的量化和架构变化来解决这个问题。

##### URL
[https://arxiv.org/abs/1702.08481](https://arxiv.org/abs/1702.08481)

##### PDF
[https://arxiv.org/pdf/1702.08481](https://arxiv.org/pdf/1702.08481)

