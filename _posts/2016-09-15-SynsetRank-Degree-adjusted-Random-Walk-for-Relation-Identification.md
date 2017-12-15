---
layout: post
title: "SynsetRank: Degree-adjusted Random Walk for Relation Identification"
date: 2016-09-15 22:46:29
categories: arXiv_CL
tags: arXiv_CL Object_Detection Knowledge Relation_Extraction Optimization Detection Relation
author: Shinichi Nakajima, Sebastian Krause, Dirk Weissenborn, Sven Schmeier, Nico Goernitz, Feiyu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In relation extraction, a key process is to obtain good detectors that find relevant sentences describing the target relation. To minimize the necessity of labeled data for refining detectors, previous work successfully made use of BabelNet, a semantic graph structure expressing relationships between synsets, as side information or prior knowledge. The goal of this paper is to enhance the use of graph structure in the framework of random walk with a few adjustable parameters. Actually, a straightforward application of random walk degrades the performance even after parameter optimization. With the insight from this unsuccessful trial, we propose SynsetRank, which adjusts the initial probability so that high degree nodes influence the neighbors as strong as low degree nodes. In our experiment on 13 relations in the FB15K-237 dataset, SynsetRank significantly outperforms baselines and the plain random walk approach.

##### Abstract (translated by Google)
在关系提取中，一个关键的过程是获得好的检测器，找到描述目标关系的相关句子。为了最大限度地减少标记数据来提炼检测器的必要性，以前的工作成功地使用了BabelNet（一种表示同义词之间关系的语义图结构）作为辅助信息或先验知识。本文的目的是在随机游走的框架下，利用一些可调参数来增强图结构的使用。实际上，即使在参数优化之后，随机游走的直接应用也降低了性能。从这个不成功的试验中我们可以看出，我们提出了调整初始概率的方法，使得高阶节点对低阶节点的影响强于邻居。在我们关于FB15K-237数据集中的13个关系的实验中，SynsetRank显着优于基线和纯随机游走方法。

##### URL
[https://arxiv.org/abs/1609.00626](https://arxiv.org/abs/1609.00626)

##### PDF
[https://arxiv.org/pdf/1609.00626](https://arxiv.org/pdf/1609.00626)

