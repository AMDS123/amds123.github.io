---
layout: post
title: "Dynamic Parallel and Distributed Graph Cuts"
date: 2016-09-12 00:31:20
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Miao Yu, Shuhan Shen, Zhanyi Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Graph-cuts are widely used in computer vision. In order to speed up the optimization process and improve the scalability for large graphs, Strandmark and Kahl introduced a splitting method to split a graph into multiple subgraphs for parallel computation in both shared and distributed memory models. However, this parallel algorithm (parallel BK-algorithm) does not have a polynomial bound on the number of iterations and is found non-convergent in some cases due to the possible multiple optimal solutions of its sub-problems. To remedy this non-convergence problem, in this work we first introduce a merging method capable of merging any number of those adjacent sub-graphs which could hardly reach an agreement on their overlapped region in the parallel BK algorithm. Based on the pseudo-boolean representations of graph cuts,our merging method is shown able to effectively reuse all the computed flows in these sub-graphs. Through both the splitting and merging, we further propose a dynamic parallel and distributed graph-cuts algorithm with guaranteed convergence to the globally optimal solutions within a predefined number of iterations. In essence, this work provides a general framework to allow more sophisticated splitting and merging strategies to be employed to further boost performance. Our dynamic parallel algorithm is validated with extensive experimental results.

##### Abstract (translated by Google)
图形切割广泛用于计算机视觉。为了加速优化过程并提高大图的可伸缩性，Strandmark和Kahl引入了一种分割方法，将共享和分布式内存模型中的图分成多个子图进行并行计算。然而，这种并行算法（并行BK算法）在迭代次数上没有多项式约束，并且在某些情况下由于其子问题可能的多重最优解而被发现是非收敛的。为了弥补这个不收敛的问题，本文首先介绍一种合并方法，该方法能够合并任意数量的在并行BK算法中难以达到其重叠区域的相邻子图。基于图的切割的伪布尔表示，我们的合并方法能够有效地重用这些子图中的所有计算流。通过分割和合并，我们进一步提出了一个动态的并行和分布式图切割算法，在预定的迭代次数内保证收敛到全局最优解。本质上，这项工作提供了一个总体框架，允许采用更复杂的分割和合并策略来进一步提升性能。我们的动态并行算法通过广泛的实验结果进行验证。

##### URL
[https://arxiv.org/abs/1512.00101](https://arxiv.org/abs/1512.00101)

##### PDF
[https://arxiv.org/pdf/1512.00101](https://arxiv.org/pdf/1512.00101)

