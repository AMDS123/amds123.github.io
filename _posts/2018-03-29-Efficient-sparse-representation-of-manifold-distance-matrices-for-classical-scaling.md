---
layout: post
title: "Efficient, sparse representation of manifold distance matrices for classical scaling"
date: 2018-03-29 17:35:03
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge
author: Javier S. Turek, Alexander Huth
mathjax: true
---

* content
{:toc}

##### Abstract
Geodesic distance matrices can reveal shape properties that are largely invariant to non-rigid deformations, and thus are often used to analyze and represent 3-D shapes. However, these matrices grow quadratically with the number of points. Thus for large point sets it is common to use a low-rank approximation to the distance matrix, which fits in memory and can be efficiently analyzed using methods such as multidimensional scaling (MDS). In this paper we present a novel sparse method for efficiently representing geodesic distance matrices using biharmonic interpolation. This method exploits knowledge of the data manifold to learn a sparse interpolation operator that approximates distances using a subset of points. We show that our method is 2x faster and uses 20x less memory than current leading methods for solving MDS on large point sets, with similar quality. This enables analyses of large point sets that were previously infeasible.

##### Abstract (translated by Google)
测地距离矩阵可以显示对非刚性变形基本不变的形状特性，因此常用于分析和表示3D形状。但是，这些矩阵随着点数的增加而呈二次方式增长。因此，对于大点集合，通常使用距离矩阵的低秩近似，该距离矩阵适合于存储器并且可以使用诸如多维缩放（MDS）的方法进行高效分析。在本文中，我们提出了一种新颖的稀疏方法，用双调和插值来有效地表示测地距离矩阵。该方法利用数据流形的知识来学习使用点子集近似距离的稀疏内插算子。我们表明，我们的方法速度提高了2倍，并且使用比当前领先方法少20倍的内存来解决大点集上的MDS，质量也差不多。这可以分析以前不可行的大点集。

##### URL
[http://arxiv.org/abs/1705.10887](http://arxiv.org/abs/1705.10887)

##### PDF
[http://arxiv.org/pdf/1705.10887](http://arxiv.org/pdf/1705.10887)

