---
layout: post
title: "MILE: A Multi-Level Framework for Scalable Graph Embedding"
date: 2018-02-26 21:18:43
categories: arXiv_AI
tags: arXiv_AI Embedding CNN Classification
author: Jiongqian Liang, Saket Gurukar, Srinivasan Parthasarathy
mathjax: true
---

* content
{:toc}

##### Abstract
Recently there has been a surge of interest in designing graph embedding methods. Few, if any, can scale to a large-sized graph with millions of nodes due to both computational complexity and memory requirements. In this paper, we relax this limitation by introducing the MultI-Level Embedding (MILE) framework -- a generic methodology allowing contemporary graph embedding methods to scale to large graphs. MILE repeatedly coarsens the graph into smaller ones using a hybrid matching technique to maintain the backbone structure of the graph. It then applies existing embedding methods on the coarsest graph and refines the embeddings to the original graph through a novel graph convolution neural network that it learns. The proposed MILE framework is agnostic to the underlying graph embedding techniques and can be applied to many existing graph embedding methods without modifying them. We employ our framework on several popular graph embedding techniques and conduct embedding for real-world graphs. Experimental results on five large-scale datasets demonstrate that MILE significantly boosts the speed (order of magnitude) of graph embedding while also often generating embeddings of better quality for the task of node classification. MILE can comfortably scale to a graph with 9 million nodes and 40 million edges, on which existing methods run out of memory or take too long to compute on a modern workstation.

##### Abstract (translated by Google)
最近，人们对图形嵌入方法的设计感兴趣。由于计算复杂性和内存需求，很少有可能扩展到具有数百万节点的大型图。在本文中，我们通过引入MultI级嵌入（MILE）框架来放宽这个限制 - 一种允许当代图嵌入方法扩展为大图的通用方法。 MILE使用混合匹配技术将图形重复粗化为较小的图形，以保持图形的骨架结构。然后它将现有的嵌入方法应用到最粗糙的图上，并通过它学习的新型图形卷积神经网络将嵌入改进为原始图。所提出的MILE框架对于底层图嵌入技术是不可知的，并且可以将其应用于许多现有的图嵌入方法而不用修改它们。我们在几种流行的图形嵌入技术中使用我们的框架，并为真实世界的图形进行嵌入。五个大规模数据集上的实验结果表明，MILE显着提高了图嵌入的速度（数量级），同时还经常为节点分类任务生成质量更好的嵌入。 MILE可以舒适地扩展到具有900万个节点和4000万个边的图形，现有方法在现有工作站上耗尽内存或花费太长时间计算。

##### URL
[http://arxiv.org/abs/1802.09612](http://arxiv.org/abs/1802.09612)

##### PDF
[http://arxiv.org/pdf/1802.09612](http://arxiv.org/pdf/1802.09612)

