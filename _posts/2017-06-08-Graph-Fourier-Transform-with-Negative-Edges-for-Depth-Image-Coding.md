---
layout: post
title: "Graph Fourier Transform with Negative Edges for Depth Image Coding"
date: 2017-06-08 06:28:34
categories: arXiv_CV
tags: arXiv_CV Relation
author: Weng-Tai Su, Gene Cheung, Chia-Wen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advent in graph signal processing (GSP) has led to the development of new graph-based transforms and wavelets for image / video coding, where the underlying graph describes inter-pixel correlations. In this paper, we develop a new transform called signed graph Fourier transform (SGFT), where the underlying graph G contains negative edges that describe anti-correlations between pixel pairs. Specifically, we first construct a one-state Markov process that models both inter-pixel correlations and anti-correlations. We then derive the corresponding precision matrix, and show that the loopy graph Laplacian matrix Q of a graph G with a negative edge and two self-loops at its end nodes is approximately equivalent. This proves that the eigenvectors of Q - called SGFT - approximates the optimal Karhunen-Lo`eve Transform (KLT). We show the importance of the self-loops in G to ensure Q is positive semi-definite. We prove that the first eigenvector of Q is piecewise constant (PWC), and thus can well approximate a piecewise smooth (PWS) signal like a depth image. Experimental results show that a block-based coding scheme based on SGFT outperforms a previous scheme using graph transforms with only positive edges for several depth images.

##### Abstract (translated by Google)
最近图形信号处理（GSP）的出现导致了图像/视频编码的新的基于图形的变换和小波的发展，其中底层图形描述了像素间的相关性。在本文中，我们开发了一种称为符号图傅里叶变换（SGFT）的新变换，其中底层图G包含描述像素对之间反相关的负边。具体来说，我们首先构建一个单一状态马尔可夫过程，模拟像素间的相关性和反相关性。然后推导出相应的精度矩阵，并证明图G中具有负边和两端自节点的图的Laplacian矩阵Q近似等价。证明了Q的特征向量称为SGFT，近似于最优的Karhunen-Loeve变换（KLT）。我们展示了G中自循环的重要性，以确保Q是正半定的。我们证明Q的第一个特征向量是分段常数（PWC），因此可以像深度图像那样很好地逼近分段平滑（PWS）信号。实验结果表明，基于SGFT的基于块的编码方案优于先前的方案，其使用仅具有正边缘的图转换来处理多个深度图像。

##### URL
[https://arxiv.org/abs/1702.03105](https://arxiv.org/abs/1702.03105)

##### PDF
[https://arxiv.org/pdf/1702.03105](https://arxiv.org/pdf/1702.03105)

