---
layout: post
title: "Activity recognition from videos with parallel hypergraph matching on GPUs"
date: 2015-05-04 10:30:47
categories: arXiv_CV
tags: arXiv_CV Sparse Recognition
author: Eric Lombardi, Christian Wolf, Oya Celiktutan, Bülent Sankur
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for activity recognition from videos based on sparse local features and hypergraph matching. We benefit from special properties of the temporal domain in the data to derive a sequential and fast graph matching algorithm for GPUs. Traditionally, graphs and hypergraphs are frequently used to recognize complex and often non-rigid patterns in computer vision, either through graph matching or point-set matching with graphs. Most formulations resort to the minimization of a difficult discrete energy function mixing geometric or structural terms with data attached terms involving appearance features. Traditional methods solve this minimization problem approximately, for instance with spectral techniques. In this work, instead of solving the problem approximatively, the exact solution for the optimal assignment is calculated in parallel on GPUs. The graphical structure is simplified and regularized, which allows to derive an efficient recursive minimization algorithm. The algorithm distributes subproblems over the calculation units of a GPU, which solves them in parallel, allowing the system to run faster than real-time on medium-end GPUs.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于稀疏局部特征和超图匹配的视频活动识别方法。我们受益于数据中时域的特殊属性，从而得到GPU的顺序和快速图匹配算法。传统上，图形和超图通常用于识别计算机视觉中的复杂且通常非刚性的图案，通过图形匹配或与图形的点集匹配。大多数配方采用混合几何或结构术语与涉及外观特征的术语的困难离散能量函数的最小化。传统方法大致上解决了这个最小化问题，例如使用光谱技术。在这项工作中，不是近似地解决问题，而是在GPU上并行计算最佳分配的精确解。图形结构被简化和规范化，从而得到一个有效的递归最小化算法。该算法将子问题分布在GPU的计算单元上，并行地解决这些问题，使系统在中端GPU上的运行速度比实时更快。

##### URL
[https://arxiv.org/abs/1505.00581](https://arxiv.org/abs/1505.00581)

##### PDF
[https://arxiv.org/pdf/1505.00581](https://arxiv.org/pdf/1505.00581)

