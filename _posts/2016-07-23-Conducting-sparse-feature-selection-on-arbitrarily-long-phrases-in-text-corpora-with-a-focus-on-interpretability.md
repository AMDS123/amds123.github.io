---
layout: post
title: "Conducting sparse feature selection on arbitrarily long phrases in text corpora with a focus on interpretability"
date: 2016-07-23 00:18:19
categories: arXiv_CL
tags: arXiv_CL Regularization Sparse Summarization Classification
author: Luke Miratrix, Robin Ackerman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a general framework for topic-specific summarization of large text corpora, and illustrate how it can be used for analysis in two quite different contexts: an OSHA database of fatality and catastrophe reports (to facilitate surveillance for patterns in circumstances leading to injury or death) and legal decisions on workers' compensation claims (to explore relevant case law). Our summarization framework, built on sparse classification methods, is a compromise between simple word frequency based methods currently in wide use, and more heavyweight, model-intensive methods such as Latent Dirichlet Allocation (LDA). For a particular topic of interest (e.g., mental health disability, or chemical reactions), we regress a labeling of documents onto the high-dimensional counts of all the other words and phrases in the documents. The resulting small set of phrases found as predictive are then harvested as the summary. Using a branch-and-bound approach, this method can be extended to allow for phrases of arbitrary length, which allows for potentially rich summarization. We discuss how focus on the purpose of the summaries can inform choices of regularization parameters and model constraints. We evaluate this tool by comparing computational time and summary statistics of the resulting word lists to three other methods in the literature. We also present a new R package, textreg. Overall, we argue that sparse methods have much to offer text analysis, and is a branch of research that should be considered further in this context.

##### Abstract (translated by Google)
我们提出了一个大型文本语料库特定主题摘要的总体框架，并说明如何将其用于两个截然不同的背景下的分析：一个OSHA数据库中的死亡和灾难报告（以方便监控导致受伤的情况下的模式或死亡）和关于工人赔偿索赔的法律裁决（探索相关判例法）。我们的基于稀疏分类方法的总结框架是在目前广泛使用的基于简单词频的方法和潜在狄利克雷分配（LDA）等更重量级的模型密集方法之间的折衷。对于感兴趣的特定主题（例如精神健康障碍或化学反应），我们将文档的标签倒退到文档中所有其他单词和短语的高维数上。然后收集所得到的作为预测的一小组短语，作为总结。使用分支定界方法，可以扩展该方法以允许任意长度的短语，这允许可能丰富的汇总。我们讨论如何集中在总结的目的可以通知正则化参数和模型约束的选择。我们通过比较计算时间和得出的单词列表的摘要统计数据与文献中的其他三种方法来评估此工具。我们还提供了一个新的R包，textreg。总的来说，我们认为稀疏的方法有很多可以提供文本分析，并且是在这方面应该进一步考虑的研究的一个分支。

##### URL
[https://arxiv.org/abs/1511.06798](https://arxiv.org/abs/1511.06798)

##### PDF
[https://arxiv.org/pdf/1511.06798](https://arxiv.org/pdf/1511.06798)

