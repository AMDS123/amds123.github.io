---
layout: post
title: "Graph-based compression of dynamic 3D point cloud sequences"
date: 2015-06-19 17:31:34
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Knowledge Relation
author: Dorina Thanou, Philip A. Chou, Pascal Frossard
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of compression of 3D point cloud sequences that are characterized by moving 3D positions and color attributes. As temporally successive point cloud frames are similar, motion estimation is key to effective compression of these sequences. It however remains a challenging problem as the point cloud frames have varying numbers of points without explicit correspondence information. We represent the time-varying geometry of these sequences with a set of graphs, and consider 3D positions and color attributes of the points clouds as signals on the vertices of the graphs. We then cast motion estimation as a feature matching problem between successive graphs. The motion is estimated on a sparse set of representative vertices using new spectral graph wavelet descriptors. A dense motion field is eventually interpolated by solving a graph-based regularization problem. The estimated motion is finally used for removing the temporal redundancy in the predictive coding of the 3D positions and the color characteristics of the point cloud sequences. Experimental results demonstrate that our method is able to accurately estimate the motion between consecutive frames. Moreover, motion estimation is shown to bring significant improvement in terms of the overall compression performance of the sequence. To the best of our knowledge, this is the first paper that exploits both the spatial correlation inside each frame (through the graph) and the temporal correlation between the frames (through the motion estimation) to compress the color and the geometry of 3D point cloud sequences in an efficient way.

##### Abstract (translated by Google)
本文针对三维点云序列的压缩问题，其特点是移动三维位置和颜色属性。由于时间上连续的点云帧是相似的，所以运动估计对于这些序列的有效压缩是关键的。然而，由于点云帧具有不同数量的点而没有明确的对应信息，所以它仍然是具有挑战性的问题。我们用一组图表来表示这些序列的时变几何图形，并且将点云的三维位置和颜色属性视为图的顶点上的信号。然后，我们将运动估计作为连续图之间的特征匹配问题。运动是使用新的谱图小波描述符在稀疏的代表顶点集上估计的。密集运动场最终通过求解基于图的正则化问题来插值。所估计的运动最终用于消除3D位置的预测编码中的时间冗余以及点云序列的颜色特性。实验结果表明，我们的方法能够准确估计连续帧之间的运动。此外，运动估计显示出在序列的整体压缩性能方面的显着改进。就我们所知，这是第一篇利用每帧内（通过图）的空间相关性和帧间的时间相关性（通过运动估计）来压缩3D点云的颜色和几何形状的论文以有效的方式进行序列。

##### URL
[https://arxiv.org/abs/1506.06096](https://arxiv.org/abs/1506.06096)

##### PDF
[https://arxiv.org/pdf/1506.06096](https://arxiv.org/pdf/1506.06096)

