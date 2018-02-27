---
layout: post
title: "GraphRNN: A Deep Generative Model for Graphs"
date: 2018-02-24 00:39:09
categories: arXiv_AI
tags: arXiv_AI RNN Quantitative
author: Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling and generating graphs is fundamental for studying networks in biology, engineering, and social sciences. However, modeling complex distributions over graphs and then efficiently sampling from these distributions is challenging due to the non-unique, high-dimensional nature of graphs and the complex, non-local dependencies that exist between edges in a given graph. Here we propose GraphRNN, a deep autoregressive model that addresses the above challenges and approximates any distribution of graphs with minimal assumptions about their structure. GraphRNN learns to generate graphs by training on a representative set of graphs and decomposes the graph generation process into a sequence of node and edge formations, conditioned on the graph structure generated so far. 
 In order to quantitatively evaluate the performance of GraphRNN, we introduce a benchmark suite of datasets, baselines and novel evaluation metrics based on Maximum Mean Discrepancy, which measure distances between sets of graphs. Our experiments show that GraphRNN significantly outperforms all baselines, learning to generate diverse graphs that match the structural characteristics of a target set, while also scaling to graphs 50 times larger than previous deep models.

##### Abstract (translated by Google)
建模和生成图是研究生物学，工程学和社会科学网络的基础。然而，由于图的非唯一性，高维性以及给定图中边之间存在复杂的非局部依赖关系，因此对图上的复杂分布进行建模并从这些分布有效地采样是具有挑战性的。在这里我们提出GraphRNN，这是一个深度自回归模型，可以解决上述挑战，并且可以用最小的假设来近似任何图的分布。 GraphRNN学习通过对代表性图集进行训练来生成图，并将图生成过程分解为节点和边形成序列，并以迄今为止生成的图结构为条件。
 为了定量评估GraphRNN的性能，我们引入了基于最大平均偏差的数据集，基线和新颖评估度量的基准套件，这些度量衡量了多组图形之间的距离。我们的实验显示GraphRNN明显优于所有基线，学习生成与目标集合的结构特征相匹配的不同图形，同时还将比以前深度模型大50倍的图形缩放。

##### URL
[http://arxiv.org/abs/1802.08773](http://arxiv.org/abs/1802.08773)

##### PDF
[http://arxiv.org/pdf/1802.08773](http://arxiv.org/pdf/1802.08773)

