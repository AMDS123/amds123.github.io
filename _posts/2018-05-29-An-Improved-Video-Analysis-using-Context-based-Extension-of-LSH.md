---
layout: post
title: "An Improved Video Analysis using Context based Extension of LSH"
date: 2018-05-29 13:49:03
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Angana Chakraborty, Sanghamitra Bandyopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
Locality Sensitive Hashing (LSH) based algorithms have already shown their promise in finding approximate nearest neighbors in high dimen- sional data space. However, there are certain scenarios, as in sequential data, where the proximity of a pair of points cannot be captured without considering their surroundings or context. In videos, as for example, a particular frame is meaningful only when it is seen in the context of its preceding and following frames. LSH has no mechanism to handle the con- texts of the data points. In this article, a novel scheme of Context based Locality Sensitive Hashing (conLSH) has been introduced, in which points are hashed together not only based on their closeness, but also because of similar context. The contribution made in this article is three fold. First, conLSH is integrated with a recently proposed fast optimal sequence alignment algorithm (FOGSAA) using a layered approach. The resultant method is applied to video retrieval for extracting similar sequences. The pro- posed algorithm yields more than 80% accuracy on an average in different datasets. It has been found to save 36.3% of the total time, consumed by the exhaustive search. conLSH reduces the search space to approximately 42% of the entire dataset, when compared with an exhaustive search by the aforementioned FOGSAA, Bag of Words method and the standard LSH implementations. Secondly, the effectiveness of conLSH is demon- strated in action recognition of the video clips, which yields an average gain of 12.83% in terms of classification accuracy over the state of the art methods using STIP descriptors. The last but of great significance is that this article provides a way of automatically annotating long and composite real life videos. The source code of conLSH is made available at <a href="http://www.isical.ac.in/~bioinfo_miu/conLSH/conLSH.html">this http URL</a>

##### Abstract (translated by Google)
基于局部敏感散列（LSH）的算法已经显示出他们在高维数据空间中找到近似最近邻居的承诺。但是，在某些情况下，如在顺序数据中，一对点的邻近不能在不考虑它们的周围环境的情况下被捕获。在视频中，例如，特定的帧仅在其前后帧出现时才有意义。 LSH没有处理数据点条件的机制。在这篇文章中，已经引入了一种基于上下文的局部敏感散列（conLSH）的新方案，其中点不仅基于它们的亲密度，而且由于相似的上下文而聚集在一起。本文所做的贡献是三倍。首先，使用分层方法将conLSH与最近提出的快速最佳序列比对算法（FOGSAA）集成。所得到的方法被应用于视频检索以提取相似的序列。所提出的算法在不同数据集中的平均准确率高达80％以上。已经发现，通过彻底搜索消耗总时间的36.3％。与上述FOGSAA，Bag of Words方法和标准LSH实施的详尽搜索相比，conLSH将搜索空间减少到整个数据集的大约42％。其次，conLSH的有效性在视频剪辑的动作识别中被证明，相对于使用STIP描述符的现有技术方法，在分类精度方面产生了12.83％的平均增益。最后一点但意义重大的是，这篇文章提供了一种自动注释长复合真实生活视频的方法。 conLSH的源代码可在<a href="http://www.isical.ac.in/~bioinfo_miu/conLSH/conLSH.html">此http URL </a>上获得

##### URL
[http://arxiv.org/abs/1705.03933](http://arxiv.org/abs/1705.03933)

##### PDF
[http://arxiv.org/e-print/1705.03933](http://arxiv.org/e-print/1705.03933)

