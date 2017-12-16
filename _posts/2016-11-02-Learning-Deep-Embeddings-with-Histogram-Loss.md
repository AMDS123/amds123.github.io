---
layout: post
title: "Learning Deep Embeddings with Histogram Loss"
date: 2016-11-02 21:48:32
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization
author: Evgeniya Ustinova, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We suggest a loss for learning deep embeddings. The new loss does not introduce parameters that need to be tuned and results in very good embeddings across a range of datasets and problems. The loss is computed by estimating two distribution of similarities for positive (matching) and negative (non-matching) sample pairs, and then computing the probability of a positive pair to have a lower similarity score than a negative pair based on the estimated similarity distributions. We show that such operations can be performed in a simple and piecewise-differentiable manner using 1D histograms with soft assignment operations. This makes the proposed loss suitable for learning deep embeddings using stochastic optimization. In the experiments, the new loss performs favourably compared to recently proposed alternatives.

##### Abstract (translated by Google)
我们建议学习深嵌入的损失。新的损失不会引入需要调整的参数，并在各种数据集和问题中产生非常好的嵌入。通过估计正匹配（匹配）和负（非匹配）样本对的相似度的两个分布，然后基于估计的相似度分布计算正对的相似度得分低于负对的概率来计算损失。我们表明，这种操作可以使用一维直方图和软分配操作以简单的分段微分方式进行。这使得所提出的损失适合于使用随机优化来学习深度嵌入。在实验中，与最近提出的替代方案相比，新损失表现良好。

##### URL
[https://arxiv.org/abs/1611.00822](https://arxiv.org/abs/1611.00822)

##### PDF
[https://arxiv.org/pdf/1611.00822](https://arxiv.org/pdf/1611.00822)

