---
layout: post
title: "Discriminative and Efficient Label Propagation on Complementary Graphs for Multi-Object Tracking"
date: 2015-12-01 17:14:36
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding Object_Tracking Detection
author: Amit Kumar K.C., Laurent Jacques, Christophe De Vleeschouwer
mathjax: true
---

* content
{:toc}

##### Abstract
Given a set of detections, detected at each time instant independently, we investigate how to associate them across time. This is done by propagating labels on a set of graphs, each graph capturing how either the spatio-temporal or the appearance cues promote the assignment of identical or distinct labels to a pair of detections. The graph construction is motivated by a locally linear embedding of the detection features. Interestingly, the neighborhood of a node in appearance graph is defined to include all the nodes for which the appearance feature is available (even if they are temporally distant). This gives our framework the uncommon ability to exploit the appearance features that are available only sporadically. Once the graphs have been defined, multi-object tracking is formulated as the problem of finding a label assignment that is consistent with the constraints captured each graph, which results into a difference of convex (DC) program. We propose to decompose the global objective function into node-wise sub-problems. This not only allows a computationally efficient solution, but also supports an incremental and scalable construction of the graph, thereby making the framework applicable to large graphs and practical tracking scenarios. Moreover, it opens the possibility of parallel implementation.

##### Abstract (translated by Google)
给定一组检测，在每个时刻独立检测，我们调查如何跨越时间关联它们。这是通过在一组图上传播标签来完成的，每个图都捕获时空或外观线索如何促进将相同或不同的标签分配给一对检测。图构造由检测特征的局部线性嵌入来激励。有趣的是，外观图中节点的邻域被定义为包括外观特征可用的所有节点（即使它们在时间上距离较远）。这使得我们的框架不常见的能力来利用仅有零星的外观特征。一旦图形已被定义，多目标跟踪被制定为寻找与每个图形捕获的约束一致的标签分配的问题，这导致凸（DC）程序的差异。我们建议将全局目标函数分解成节点子问题。这不仅使计算有效的解决方案，而且还支持图的增量和可扩展的构造，从而使框架适用于大图和实际的跟踪场景。而且，它开启了并行实施的可能性。

##### URL
[https://arxiv.org/abs/1504.01124](https://arxiv.org/abs/1504.01124)

##### PDF
[https://arxiv.org/pdf/1504.01124](https://arxiv.org/pdf/1504.01124)

