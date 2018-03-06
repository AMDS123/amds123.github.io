---
layout: post
title: "Complexity Analysis and Efficient Measurement Selection Primitives for High-Rate Graph SLAM"
date: 2018-03-02 20:55:35
categories: arXiv_RO
tags: arXiv_RO Optimization Quantitative SLAM
author: Kristoffer M. Frey, Ted J. Steiner, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
Sparsity has been widely recognized as crucial for efficient optimization in graph-based SLAM. Because the sparsity and structure of the SLAM graph reflect the set of incorporated measurements, many methods for sparsification have been proposed in hopes of reducing computation. These methods often focus narrowly on reducing edge count without regard for structure at a global level. Such structurally-naive techniques can fail to produce significant computational savings, even after aggressive pruning. In contrast, simple heuristics such as measurement decimation and keyframing are known empirically to produce significant computation reductions. To demonstrate why, we propose a quantitative metric called elimination complexity (EC) that bridges the existing analytic gap between graph structure and computation. EC quantifies the complexity of the primary computational bottleneck: the factorization step of a Gauss-Newton iteration. Using this metric, we show rigorously that decimation and keyframing impose favorable global structures and therefore achieve computation reductions on the order of $r^2/9$ and $r^3$, respectively, where $r$ is the pruning rate. We additionally present numerical results showing EC provides a good approximation of computation in both batch and incremental (iSAM2) optimization and demonstrate that pruning methods promoting globally-efficient structure outperform those that do not.

##### Abstract (translated by Google)
稀疏性已被广泛认为是基于图形的SLAM中高效优化的关键。由于SLAM图的稀疏性和结构反映了所包含的测量集，所以已经提出了许多用于稀疏化的方法，希望减少计算。这些方法往往侧重于减少边缘数量，而不考虑全球层面的结构。这种结构朴素的技术可能无法产生显着的计算节省，即使在积极的修剪之后。相比之下，简单的启发式算法如测量抽取和关键帧在经验上是已知的，可以产生显着的计算量减少。为了说明原因，我们提出了一种称为消除复杂性（EC）的量化度量，它弥合了图结构和计算之间现有的分析差距。 EC量化了主要计算瓶颈的复杂性：高斯 - 牛顿迭代的分解步骤。使用这个度量，我们严格地展示了抽取和关键帧强加了有利的全局结构，因此分别实现了$ r ^ 2/9 $和$ r ^ 3 $的计算量减少，其中$ r $是修剪率。我们还提供了数值结果，显示EC提供了批量和增量（iSAM2）优化中的计算的良好近似，并且证明了促进全局有效结构的修剪方法优于那些没有的结构。

##### URL
[http://arxiv.org/abs/1709.06821](http://arxiv.org/abs/1709.06821)

##### PDF
[http://arxiv.org/pdf/1709.06821](http://arxiv.org/pdf/1709.06821)

