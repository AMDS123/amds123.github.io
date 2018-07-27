---
layout: post
title: "Adaptively Transforming Graph Matching"
date: 2018-07-26 14:12:40
categories: arXiv_CV
tags: arXiv_CV QA Optimization
author: Fudong Wang, Nan Xue, Yipeng Zhang, Xiang Bai, Gui-Song Xia
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, many graph matching methods that incorporate pairwise constraint and that can be formulated as a quadratic assignment problem (QAP) have been proposed. Although these methods demonstrate promising results for the graph matching problem, they have high complexity in space or time. In this paper, we introduce an adaptively transforming graph matching (ATGM) method from the perspective of functional representation. More precisely, under a transformation formulation, we aim to match two graphs by minimizing the discrepancy between the original graph and the transformed graph. With a linear representation map of the transformation, the pairwise edge attributes of graphs are explicitly represented by unary node attributes, which enables us to reduce the space and time complexity significantly. Due to an efficient Frank-Wolfe method-based optimization strategy, we can handle graphs with hundreds and thousands of nodes within an acceptable amount of time. Meanwhile, because transformation map can preserve graph structures, a domain adaptation-based strategy is proposed to remove the outliers. The experimental results demonstrate that our proposed method outperforms the state-of-the-art graph matching algorithms.

##### Abstract (translated by Google)
最近，已经提出了许多结合成对约束并且可以表述为二次分配问题（QAP）的图匹配方法。尽管这些方法对于图匹配问题展示了有希望的结果，但它们在空间或时间上具有高度复杂性。在本文中，我们从功能表示的角度介绍了自适应变换图匹配（ATGM）方法。更确切地说，在转换公式下，我们的目标是通过最小化原始图和转换图之间的差异来匹配两个图。利用变换的线性表示图，图的成对边缘属性由一元节点属性明确表示，这使我们能够显着减少空间和时间复杂度。由于基于Frank-Wolfe方法的高效优化策略，我们可以在可接受的时间内处理具有数百个节点的图形。同时，由于变换图可以保留图结构，因此提出了一种基于域自适应的策略来消除异常值。实验结果表明，我们提出的方法优于最先进的图匹配算法。

##### URL
[http://arxiv.org/abs/1807.10160](http://arxiv.org/abs/1807.10160)

##### PDF
[http://arxiv.org/pdf/1807.10160](http://arxiv.org/pdf/1807.10160)

