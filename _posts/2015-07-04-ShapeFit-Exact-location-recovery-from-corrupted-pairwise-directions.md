---
layout: post
title: "ShapeFit: Exact location recovery from corrupted pairwise directions"
date: 2015-07-04 04:51:53
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Paul Hand, Choongbum Lee, Vladislav Voroninski
mathjax: true
---

* content
{:toc}

##### Abstract
Let $t_1,\ldots,t_n \in \mathbb{R}^d$ and consider the location recovery problem: given a subset of pairwise direction observations $\{(t_i - t_j) / \|t_i - t_j\|_2\}_{i<j \in [n] \times [n]}$, where a constant fraction of these observations are arbitrarily corrupted, find $\{t_i\}_{i=1}^n$ up to a global translation and scale. We propose a novel algorithm for the location recovery problem, which consists of a simple convex program over $dn$ real variables. We prove that this program recovers a set of $n$ i.i.d. Gaussian locations exactly and with high probability if the observations are given by an \erdosrenyi graph, $d$ is large enough, and provided that at most a constant fraction of observations involving any particular location are adversarially corrupted. We also prove that the program exactly recovers Gaussian locations for $d=3$ if the fraction of corrupted observations at each location is, up to poly-logarithmic factors, at most a constant. Both of these recovery theorems are based on a set of deterministic conditions that we prove are sufficient for exact recovery.

##### Abstract (translated by Google)
假设$ t_1，\ ldots，t_n \ in \ mathbb {R} ^ d $，并考虑位置恢复问题：给定配对方向观测子集$ \ {在这些观测值的一个常数部分被任意地破坏的情况下，找到一个全局的全局最优解{$ ij}翻译和规模。我们提出了一种位置恢复问题的新算法，该算法由一个简单的凸函数组成，该函数包含$ dn $ real变量。我们证明这个程序恢复了一组$ n $ i.i.d.如果观测值是由\ erdosrenyi图给出的，那么高斯定位就是高概率的，且$ d $足够大，并且假定涉及任何特定位置的观测值的最小值都会被对抗地破坏。我们还证明，如果每个位置的损坏观测的分数是多对数因子，最多是一个常数，那么程序恰好恢复高斯位置$ d = 3 $。这两个恢复定理都是基于一系列确定性条件，我们证明这些条件对于精确恢复是足够的。

##### URL
[https://arxiv.org/abs/1506.01437](https://arxiv.org/abs/1506.01437)

##### PDF
[https://arxiv.org/pdf/1506.01437](https://arxiv.org/pdf/1506.01437)

