---
layout: post
title: "On Transitive Consistency for Linear Invertible Transformations between Euclidean Coordinate Systems"
date: 2015-09-02 14:57:16
categories: arXiv_CV
tags: arXiv_CV Relation
author: Johan Thunberg, Florian Bernard, Jorge Goncalves
mathjax: true
---

* content
{:toc}

##### Abstract
Transitive consistency is an intrinsic property for collections of linear invertible transformations between Euclidean coordinate frames. In practice, when the transformations are estimated from data, this property is lacking. This work addresses the problem of synchronizing transformations that are not transitively consistent. Once the transformations have been synchronized, they satisfy the transitive consistency condition - a transformation from frame $A$ to frame $C$ is equal to the composite transformation of first transforming A to B and then transforming B to C. The coordinate frames correspond to nodes in a graph and the transformations correspond to edges in the same graph. Two direct or centralized synchronization methods are presented for different graph topologies; the first one for quasi-strongly connected graphs, and the second one for connected graphs. As an extension of the second method, an iterative Gauss-Newton method is presented, which is later adapted to the case of affine and Euclidean transformations. Two distributed synchronization methods are also presented for orthogonal matrices, which can be seen as distributed versions of the two direct or centralized methods; they are similar in nature to standard consensus protocols used for distributed averaging. When the transformations are orthogonal matrices, a bound on the optimality gap can be computed. Simulations show that the gap is almost right, even for noise large in magnitude. This work also contributes on a theoretical level by providing linear algebraic relationships for transitively consistent transformations. One of the benefits of the proposed methods is their simplicity - basic linear algebraic methods are used, e.g., the Singular Value Decomposition (SVD). For a wide range of parameter settings, the methods are numerically validated.

##### Abstract (translated by Google)
传递一致性是欧几里德坐标系之间线性可逆变换集合的一个固有属性。在实践中，当从数据估计变换时，这个属性是缺乏的。这项工作解决了同步不是过渡一致的转换的问题。一旦变换已经同步，它们满足传递一致性条件 - 从帧$ A $到帧$ C $的变换等于第一变换A到B然后变换B到C的复合变换。坐标帧对应于图中的节点，并且变换对应于同一图中的边。针对不同的图形拓扑提出了两种直接或集中的同步方法;第一个是准强连通图，第二个是连通图。作为第二种方法的扩展，提出了一种迭代高斯 - 牛顿方法，后来适应仿射和欧几里德变换的情况。对于正交矩阵也提出了两种分布式同步方法，可以看作是两种直接或集中式方法的分布式版本;它们在性质上与用于分布式求平均的标准共识协议相似。当变换是正交矩阵时，可以计算最优性间隙的界限。模拟结果表明，差距几乎是正确的，即使对于数量巨大的噪声。这项工作也为理论层面提供了线性代数关系的传递一致转换。所提出方法的优点之一是其简单性 - 使用基本的线性代数方法，例如奇异值分解（SVD）。对于广泛的参数设置，这些方法进行数字验证。

##### URL
[https://arxiv.org/abs/1509.00728](https://arxiv.org/abs/1509.00728)

##### PDF
[https://arxiv.org/pdf/1509.00728](https://arxiv.org/pdf/1509.00728)

