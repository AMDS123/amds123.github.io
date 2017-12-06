---
layout: post
title: "Fast and Exact Top-k Search for Random Walk with Restart"
date: 2012-01-31 15:09:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Yasuhiro Fujiwara, Makoto Nakatsuji, Makoto Onizuka, Masaru Kitsuregawa
mathjax: true
---

* content
{:toc}

##### Abstract
Graphs are fundamental data structures and have been employed for centuries to model real-world systems and phenomena. Random walk with restart (RWR) provides a good proximity score between two nodes in a graph, and it has been successfully used in many applications such as automatic image captioning, recommender systems, and link prediction. The goal of this work is to find nodes that have top-k highest proximities for a given node. Previous approaches to this problem find nodes efficiently at the expense of exactness. The main motivation of this paper is to answer, in the affirmative, the question, `Is it possible to improve the search time without sacrificing the exactness?'. Our solution, {it K-dash}, is based on two ideas: (1) It computes the proximity of a selected node efficiently by sparse matrices, and (2) It skips unnecessary proximity computations when searching for the top-k nodes. Theoretical analyses show that K-dash guarantees result exactness. We perform comprehensive experiments to verify the efficiency of K-dash. The results show that K-dash can find top-k nodes significantly faster than the previous approaches while it guarantees exactness.

##### Abstract (translated by Google)
图表是基本的数据结构，几个世纪以来就被用来模拟现实世界的系统和现象。随机行走重启（RWR）在图形中的两个节点之间提供了良好的邻近分数，并且已经成功用于许多应用，例如自动图像字幕，推荐系统和链接预测。这项工作的目标是找到给定节点具有top-k最高近似值的节点。以前的这个问题的方法是以牺牲精确性为代价来有效地找到节点。本文的主要动机是回答肯定的问题：“是否有可能在不牺牲准确性的情况下提高搜索时间？”。我们的解决方案是基于两个思路：（1）通过稀疏矩阵有效地计算选定节点的接近度;（2）当搜索前k个节点时，跳过不必要的接近度计算。理论分析表明K-dash保证了结果的正确性。我们进行全面的实验来验证K-dash的效率。结果表明，K-dash在保证正确性的前提下可以比以前的方法快速找到top-k节点。

##### URL
[https://arxiv.org/abs/1201.6566](https://arxiv.org/abs/1201.6566)

