---
layout: post
title: "Product Graph-based Higher Order Contextual Similarities for Inexact Subgraph Matching"
date: 2017-02-01 18:53:53
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Anjan Dutta, Josep Lladós, Horst Bunke, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Many algorithms formulate graph matching as an optimization of an objective function of pairwise quantification of nodes and edges of two graphs to be matched. Pairwise measurements usually consider local attributes but disregard contextual information involved in graph structures. We address this issue by proposing contextual similarities between pairs of nodes. This is done by considering the tensor product graph (TPG) of two graphs to be matched, where each node is an ordered pair of nodes of the operand graphs. Contextual similarities between a pair of nodes are computed by accumulating weighted walks (normalized pairwise similarities) terminating at the corresponding paired node in TPG. Once the contextual similarities are obtained, we formulate subgraph matching as a node and edge selection problem in TPG. We use contextual similarities to construct an objective function and optimize it with a linear programming approach. Since random walk formulation through TPG takes into account higher order information, it is not a surprise that we obtain more reliable similarities and better discrimination among the nodes and edges. Experimental results shown on synthetic as well as real benchmarks illustrate that higher order contextual similarities add discriminating power and allow one to find approximate solutions to the subgraph matching problem.

##### Abstract (translated by Google)
许多算法将图匹配作为要匹配的两个图的节点和边的成对量化的目标函数的优化来进行。成对测量通常考虑局部属性，但不考虑图形结构中涉及的上下文信息。我们通过提出节点对之间的上下文相似性来解决这个问题。这是通过考虑要匹配的两个图的张量乘积图（TPG）来完成的，其中每个节点是操作数图的有序节点对。一对节点之间的上下文相似性通过累加终止于TPG中的对应配对节点的加权走（归一化成对相似性）来计算。一旦获得上下文相似性，我们将子图匹配作为TPG中的节点和边缘选择问题。我们使用上下文相似性来构造一个目标函数，并用线性规划方法对其进行优化。由于通过TPG的随机游走公式考虑了更高阶的信息，所以我们获得更可靠的相似性和节点和边缘之间的更好的区分并不意外。在合成和实际基准测试中显示的实验结果表明，高阶上下文相似性增加了区分能力，并允许找到子图匹配问题的近似解。

##### URL
[https://arxiv.org/abs/1702.00391](https://arxiv.org/abs/1702.00391)

##### PDF
[https://arxiv.org/pdf/1702.00391](https://arxiv.org/pdf/1702.00391)

