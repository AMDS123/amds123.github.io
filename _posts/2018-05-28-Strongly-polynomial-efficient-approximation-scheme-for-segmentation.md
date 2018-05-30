---
layout: post
title: "Strongly polynomial efficient approximation scheme for segmentation"
date: 2018-05-28 20:55:47
categories: arXiv_AI
tags: arXiv_AI Segmentation Optimization
author: Nikolaj Tatti
mathjax: true
---

* content
{:toc}

##### Abstract
Partitioning a sequence of length $n$ into $k$ coherent segments is one of the classic optimization problems. As long as the optimization criterion is additive, the problem can be solved exactly in $O(n^2k)$ time using a classic dynamic program. Due to the quadratic term, computing the exact segmentation may be too expensive for long sequences, which has led to development of approximate solutions. We consider an existing estimation scheme that computes $(1 + \epsilon)$ approximation in polylogarithmic time. We augment this algorithm, making it strongly polynomial. We do this by first solving a slightly different segmentation problem, where the quality of the segmentation is the maximum penalty of an individual segment. By using this solution to initialize the estimation scheme, we are able to obtain a strongly polynomial algorithm. In addition, we consider a cumulative version of the problem, where we are asked to discover the optimal segmentation for each prefix of the input sequence. We propose a strongly polynomial algorithm that yields $(1 + \epsilon)$ approximation in $O(nk^2 / \epsilon)$ time. Finally, we consider a cumulative version of the maximum segmentation, and show that this can be solved in $O(nk \log k)$ time.

##### Abstract (translated by Google)
将长度为$ n $的序列划分为$ k $连贯的片段是经典优化问题之一。只要优化标准具有可加性，就可以使用经典动态程序在$ O（n ^ 2k）$ time中准确解决问题。由于二次项，计算精确分割对于长序列来说可能太昂贵，这导致了近似解的发展。我们考虑一个现有的估计方案，计算多对数时间的$（1 +ε）近似值。我们增加这个算法，使它成为强多项式。我们首先解决一个稍微不同的分割问题，其中分割的质量是单个分割的最大惩罚。通过使用此解决方案来初始化估计方案，我们能够获得强多项式算法。另外，我们考虑一个累积版本的问题，我们被要求为输入序列的每个前缀发现最佳分割。我们提出了一个强多项式算法，在$ O（nk ^ 2 /ε）$ time中产生$（1 +ε）近似值。最后，我们考虑最大分割的累积版本，并且显示这可以在$ O（nk \ log k）$ time中解决。

##### URL
[http://arxiv.org/abs/1805.11170](http://arxiv.org/abs/1805.11170)

##### PDF
[http://arxiv.org/pdf/1805.11170](http://arxiv.org/pdf/1805.11170)

