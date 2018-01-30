---
layout: post
title: "Efficient Hierarchical Graph-Based Segmentation of RGBD Videos"
date: 2018-01-26 21:21:25
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Steven Hickson, Stan Birchfield, Irfan Essa, Henrik Christensen
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient and scalable algorithm for segmenting 3D RGBD point clouds by combining depth, color, and temporal information using a multistage, hierarchical graph-based approach. Our algorithm processes a moving window over several point clouds to group similar regions over a graph, resulting in an initial over-segmentation. These regions are then merged to yield a dendrogram using agglomerative clustering via a minimum spanning tree algorithm. Bipartite graph matching at a given level of the hierarchical tree yields the final segmentation of the point clouds by maintaining region identities over arbitrarily long periods of time. We show that a multistage segmentation with depth then color yields better results than a linear combination of depth and color. Due to its incremental processing, our algorithm can process videos of any length and in a streaming pipeline. The algorithm's ability to produce robust, efficient segmentation is demonstrated with numerous experimental results on challenging sequences from our own as well as public RGBD data sets.

##### Abstract (translated by Google)
我们提出了一种高效的可扩展算法，通过结合深度，颜色和时间信息，使用多级分层图形方法来分割3D RGBD点云。我们的算法在几个点云上处理一个移动窗口，在图上对相似的区域进行分组，导致初始的过分割。然后将这些区域合并以通过最小生成树算法使用凝聚聚类来产生树状图。通过在任意长的时间段内保持区域标识，分层树的给定级别的二分图匹配产生点云的最终分割。我们显示深度和颜色的多级分割产生比深度和颜色的线性组合更好的结果。由于它的增量处理，我们的算法可以处理任何长度的视频和流媒体流水线。该算法的能力，产生强大的，有效的分割与众多实验结果表明，从我们自己的以及公开的RGBD数据集的挑战性的序列。

##### URL
[http://arxiv.org/abs/1801.08981](http://arxiv.org/abs/1801.08981)

##### PDF
[http://arxiv.org/pdf/1801.08981](http://arxiv.org/pdf/1801.08981)

