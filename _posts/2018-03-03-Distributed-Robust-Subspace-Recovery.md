---
layout: post
title: "Distributed Robust Subspace Recovery"
date: 2018-03-03 21:31:02
categories: arXiv_AI
tags: arXiv_AI
author: Vahan Huroyan, Gilad Lerman
mathjax: true
---

* content
{:toc}

##### Abstract
We study Robust Subspace Recovery (RSR) in distributed settings. We consider a huge dataset in an ad hoc network without a central processor, where each node has access only to one chunk of the dataset. We assume that part of the whole dataset lies around a low-dimensional subspace and the other part is composed of outliers that lie away from that subspace. The goal is to recover the underlying subspace for the whole dataset, without transferring the data itself between the nodes. We apply the Consensus-Based Gradient method for the Geometric Median Subspace algorithm for RSR. We propose an iterative solution for the local dual minimization problem and establish its $r$-linear convergence. We also explain how to distributedly implement the Reaper and Fast Median Subspace algorithms for RSR. We demonstrate the competitive performance of our algorithms for both synthetic and real data.

##### Abstract (translated by Google)
我们在分布式设置中研究鲁棒子空间恢复（RSR）。我们考虑一个没有中央处理器的ad hoc网络中的巨大数据集，其中每个节点只能访问数据集的一个块。我们假设整个数据集的一部分位于低维子空间的周围，另一部分由离开该子空间的离群值组成。目标是为整个数据集恢复底层子空间，而不在节点之间传输数据本身。我们将用于RSR的几何中值子空间算法应用基于共识的梯度方法。我们提出了一个局部对偶最小化问题的迭代解，并建立了它的$ r $线性收敛。我们还解释了如何分布式实现RSR的Reaper和Fast Median Subspace算法。我们证明了我们的算法对于合成和真实数据的竞争性表现。

##### URL
[http://arxiv.org/abs/1705.09382](http://arxiv.org/abs/1705.09382)

##### PDF
[http://arxiv.org/pdf/1705.09382](http://arxiv.org/pdf/1705.09382)

