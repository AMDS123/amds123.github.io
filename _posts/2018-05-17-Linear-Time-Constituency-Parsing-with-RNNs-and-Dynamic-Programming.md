---
layout: post
title: "Linear-Time Constituency Parsing with RNNs and Dynamic Programming"
date: 2018-05-17 23:40:06
categories: arXiv_CL
tags: arXiv_CL RNN Detection
author: Juneki Hong, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, span-based constituency parsing has achieved competitive accuracies with extremely simple models by using bidirectional RNNs to model "spans". However, the minimal span parser of Stern et al (2017a) which holds the current state of the art accuracy is a chart parser running in cubic time, $O(n^3)$, which is too slow for longer sentences and for applications beyond sentence boundaries such as end-to-end discourse parsing and joint sentence boundary detection and parsing. We propose a linear-time constituency parser with RNNs and dynamic programming using graph-structured stack and beam search, which runs in time $O(n b^2)$ where $b$ is the beam size. We further speed this up to $O(n b\log b)$ by integrating cube pruning. Compared with chart parsing baselines, this linear-time parser is substantially faster for long sentences on the Penn Treebank and orders of magnitude faster for discourse parsing, and achieves the highest F1 accuracy on the Penn Treebank among single model end-to-end systems.

##### Abstract (translated by Google)
最近，基于跨度的选区分析通过使用双向RNN对“跨度”进行建模，获得了具有极其简单模型的竞争精度。然而，Stern等人（2017a）的最小跨度解析器（其持有当前最先进的精确度）是以立方时间运行的图表解析器，$ O（n ^ 3）$，对于较长的句子和应用来说太慢超出了句子边界，如端到端的话语分析和联合句子边界检测和解析。我们提出了一个带有RNN的线性时间选区解析器和使用图形结构堆栈和波束搜索的动态规划，其运行时间为$ O（n b ^ 2）$，其中$ b $是波束的大小。我们通过集成多维数据集修剪进一步加速到$ O（n b \ log b）$。与图表解析基线相比，Penn Treebank中的长句子的线性时间解析器速度快得多，话语解析速度也快得多，并且在单一模型端到端系统中实现了Penn Treebank中最高的F1准确性。

##### URL
[http://arxiv.org/abs/1805.06995](http://arxiv.org/abs/1805.06995)

##### PDF
[http://arxiv.org/pdf/1805.06995](http://arxiv.org/pdf/1805.06995)

