---
layout: post
title: "EFANNA : An Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph"
date: 2016-12-03 06:31:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention
author: Cong Fu, Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Approximate nearest neighbor (ANN) search is a fundamental problem in many areas of data mining, machine learning and computer vision. The performance of traditional hierarchical structure (tree) based methods decreases as the dimensionality of data grows, while hashing based methods usually lack efficiency in practice. Recently, the graph based methods have drawn considerable attention. The main idea is that \emph{a neighbor of a neighbor is also likely to be a neighbor}, which we refer as \emph{NN-expansion}. These methods construct a $k$-nearest neighbor ($k$NN) graph offline. And at online search stage, these methods find candidate neighbors of a query point in some way (\eg, random selection), and then check the neighbors of these candidate neighbors for closer ones iteratively. Despite some promising results, there are mainly two problems with these approaches: 1) These approaches tend to converge to local optima. 2) Constructing a $k$NN graph is time consuming. We find that these two problems can be nicely solved when we provide a good initialization for NN-expansion. In this paper, we propose EFANNA, an extremely fast approximate nearest neighbor search algorithm based on $k$NN Graph. Efanna nicely combines the advantages of hierarchical structure based methods and nearest-neighbor-graph based methods. Extensive experiments have shown that EFANNA outperforms the state-of-art algorithms both on approximate nearest neighbor search and approximate nearest neighbor graph construction. To the best of our knowledge, EFANNA is the fastest algorithm so far both on approximate nearest neighbor graph construction and approximate nearest neighbor search. A library EFANNA based on this research is released on Github.

##### Abstract (translated by Google)
近似最近邻（ANN）搜索是数据挖掘，机器学习和计算机视觉等许多领域的基本问题。传统的基于层次结构（tree）的方法的性能随着数据维度的增长而降低，而基于散列的方法通常在实践中缺乏效率。最近，基于图的方法引起了相当的关注。主要思想是\ emph {邻居的邻居也可能是邻居}，我们称之为\ NN {扩展}。这些方法离线构造一个$ k $  - 最近的邻居（$ k $ NN）图。而在在线搜索阶段，这些方法以某种方式（例如，随机选择）找到查询点的候选邻居，然后迭代地检查这些候选邻居的邻居。尽管取得了一些有希望的结果，但这些方法主要存在两个问题：1）这些方法倾向于趋于局部最优。 2）构造$ k $ NN图是耗时的。我们发现这两个问题可以很好的解决，当我们提供一个好的NN扩展初始化。在本文中，我们提出EFANNA，一种基于$ k $ NN图的极快近似最近邻搜索算法。 Efanna很好地结合了基于层次结构的方法和基于最近邻图的方法的优点。大量的实验表明，EFANNA在近似最近邻搜索和近似最近邻图构造方面都优于现有算法。就我们所知，EFANNA是近似最近邻图构造和近似最近邻搜索中最快的算法。基于这项研究的图书馆EFANNA在Github上发布。

##### URL
[https://arxiv.org/abs/1609.07228](https://arxiv.org/abs/1609.07228)

##### PDF
[https://arxiv.org/pdf/1609.07228](https://arxiv.org/pdf/1609.07228)

