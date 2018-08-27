---
layout: post
title: "Measuring LDA Topic Stability from Clusters of Replicated Runs"
date: 2018-08-24 11:37:40
categories: arXiv_CL
tags: arXiv_CL
author: Mika M&#xe4;ntyl&#xe4;, Ma&#xeb;lick Claes, Umar Farooq
mathjax: true
---

* content
{:toc}

##### Abstract
Background: Unstructured and textual data is increasing rapidly and Latent Dirichlet Allocation (LDA) topic modeling is a popular data analysis methods for it. Past work suggests that instability of LDA topics may lead to systematic errors. Aim: We propose a method that relies on replicated LDA runs, clustering, and providing a stability metric for the topics. Method: We generate k LDA topics and replicate this process n times resulting in n*k topics. Then we use K-medioids to cluster the n*k topics to k clusters. The k clusters now represent the original LDA topics and we present them like normal LDA topics showing the ten most probable words. For the clusters, we try multiple stability metrics, out of which we recommend Rank-Biased Overlap, showing the stability of the topics inside the clusters. Results: We provide an initial validation where our method is used for 270,000 Mozilla Firefox commit messages with k=20 and n=20. We show how our topic stability metrics are related to the contents of the topics. Conclusions: Advances in text mining enable us to analyze large masses of text in software engineering but non-deterministic algorithms, such as LDA, may lead to unreplicable conclusions. Our approach makes LDA stability transparent and is also complementary rather than alternative to many prior works that focus on LDA parameter tuning.

##### Abstract (translated by Google)
背景：非结构化和文本数据正在迅速增加，潜在Dirichlet分配（LDA）主题建模是一种流行的数据分析方法。过去的工作表明，LDA主题的不稳定性可能导致系统性错误。目标：我们提出了一种依赖于复制的LDA运行，聚类以及为主题提供稳定性度量的方法。方法：我们生成k个LDA主题并复制此过程n次，从而产生n * k个主题。然后我们使用K-medioids将n * k个主题聚类为k个聚类。 k簇现在代表了原始的LDA主题，我们将它们呈现为正常的LDA主题，显示十个最可能的单词。对于集群，我们尝试多个稳定性指标，我们建议使用Rank-Biased Overlap，显示集群内主题的稳定性。结果：我们提供初始验证，其中我们的方法用于270,000个Mozilla Firefox提交消息，其中k = 20且n = 20。我们将展示我们的主题稳定性指标如何与主题的内容相关联。结论：文本挖掘的进步使我们能够分析软件工程中的大量文本，但非确定性算法（如LDA）可能会导致无法解释的结论。我们的方法使LDA稳定性透明，并且也是许多先前关注LDA参数调整的工作的补充而非替代。

##### URL
[http://arxiv.org/abs/1808.08098](http://arxiv.org/abs/1808.08098)

##### PDF
[http://arxiv.org/pdf/1808.08098](http://arxiv.org/pdf/1808.08098)

