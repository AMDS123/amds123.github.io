---
layout: post
title: "Subspace clustering based on low rank representation and weighted nuclear norm minimization"
date: 2016-10-14 03:08:52
categories: arXiv_CV
tags: arXiv_CV
author: Yu Song, Yiquan Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering refers to the problem of segmenting a set of data points approximately drawn from a union of multiple linear subspaces. Aiming at the subspace clustering problem, various subspace clustering algorithms have been proposed and low rank representation based subspace clustering is a very promising and efficient subspace clustering algorithm. Low rank representation method seeks the lowest rank representation among all the candidates that can represent the data points as linear combinations of the bases in a given dictionary. Nuclear norm minimization is adopted to minimize the rank of the representation matrix. However, nuclear norm is not a very good approximation of the rank of a matrix and the representation matrix thus obtained can be of high rank which will affect the final clustering accuracy. Weighted nuclear norm (WNN) is a better approximation of the rank of a matrix and WNN is adopted in this paper to describe the rank of the representation matrix. The convex program is solved via conventional alternation direction method of multipliers (ADMM) and linearized alternating direction method of multipliers (LADMM) and they are respectively refer to as WNNM-LRR and WNNM-LRR(L). Experimental results show that, compared with low rank representation method and several other state-of-the-art subspace clustering methods, WNNM-LRR and WNNM-LRR(L) can get higher clustering accuracy.

##### Abstract (translated by Google)
子空间聚类是指分割从多个线性子空间的联合近似绘制的一组数据点的问题。针对子空间聚类问题，提出了各种子空间聚类算法，基于低秩表示的子空间聚类算法是一种非常有前途和有效的子空间聚类算法。低等级表示法在所有可以表示数据点的候选中搜索最低等级表示，作为给定字典中的基的线性组合。采用核范数最小化来最小化表示矩阵的秩。但是，核范数并不是一个矩阵秩的很好的近似值，因此得到的表示矩阵可能是高阶的，这将影响最终的聚类精度。加权核范数（WNN）是矩阵秩的较好近似，本文采用WNN来描述矩阵的秩。凸规划是通过传统的乘法器交替方向法（ADMM）和乘法器线性化交替方向法（LADMM）求解的，分别称为WNNM-LRR和WNNM-LRR（L）。实验结果表明，与低秩表示法和其他一些现有的子空间聚类方法相比，WNNM-LRR和WNNM-LRR（L）可以获得更高的聚类精度。

##### URL
[https://arxiv.org/abs/1610.03604](https://arxiv.org/abs/1610.03604)

##### PDF
[https://arxiv.org/pdf/1610.03604](https://arxiv.org/pdf/1610.03604)

