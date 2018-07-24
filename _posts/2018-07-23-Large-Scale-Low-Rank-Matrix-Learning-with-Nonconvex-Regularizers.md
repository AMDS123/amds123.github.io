---
layout: post
title: "Large-Scale Low-Rank Matrix Learning with Nonconvex Regularizers"
date: 2018-07-23 17:10:20
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Quanming Yao, James T.Kwok, Taifeng Wang, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Low-rank modeling has many important applications in computer vision and machine learning. While the matrix rank is often approximated by the convex nuclear norm, the use of nonconvex low-rank regularizers has demonstrated better empirical performance. However, the resulting optimization problem is much more challenging. Recent state-of-the-art requires an expensive full SVD in each iteration. In this paper, we show that for many commonly-used nonconvex low-rank regularizers, a cutoff can be derived to automatically threshold the singular values obtained from the proximal operator. This allows such operator being efficiently approximated by power method. Based on it, we develop a proximal gradient algorithm (and its accelerated variant) with inexact proximal splitting and prove that a convergence rate of O(1/T) where T is the number of iterations is guaranteed. Furthermore, we show the proposed algorithm can be well parallelized, which achieves nearly linear speedup w.r.t the number of threads. Extensive experiments are performed on matrix completion and robust principal component analysis, which shows a significant speedup over the state-of-the-art. Moreover, the matrix solution obtained is more accurate and has a lower rank than that of the nuclear norm regularizer.

##### Abstract (translated by Google)
低秩建模在计算机视觉和机器学习中有许多重要的应用。虽然矩阵秩通常由凸核范数近似，但非凸低阶正则化器的使用已经证明了更好的经验性能。但是，由此产生的优化问题更具挑战性。最近的现有技术在每次迭代中需要昂贵的全SVD。在本文中，我们展示了对于许多常用的非凸低阶正则化器，可以导出截止值以自动阈值从近端算子获得的奇异值。这允许通过功率方法有效地近似这样的操作者。在此基础上，我们开发了近端梯度算法（及其加速变量），并且不精确的近端分裂，并证明了O（1 / T）的收敛速度，其中T是迭代次数。此外，我们证明了所提出的算法可以很好地并行化，从而实现了线程数的近似线性加速。对矩阵完成和稳健的主成分分析进行了广泛的实验，这显示了相对于现有技术的显着加速。而且，所获得的基质溶液更准确并且具有比核标准正则化器更低的等级。

##### URL
[http://arxiv.org/abs/1708.00146](http://arxiv.org/abs/1708.00146)

##### PDF
[http://arxiv.org/pdf/1708.00146](http://arxiv.org/pdf/1708.00146)

