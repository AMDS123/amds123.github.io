---
layout: post
title: "Exact simultaneous recovery of locations and structure from known orientations and corrupted point correspondences"
date: 2015-09-16 20:56:53
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Paul Hand, Choongbum Lee, Vladislav Voroninski
mathjax: true
---

* content
{:toc}

##### Abstract
Let $t_1,\ldots,t_{n_l} \in \mathbb{R}^d$ and $p_1,\ldots,p_{n_s} \in \mathbb{R}^d$ and consider the bipartite location recovery problem: given a subset of pairwise direction observations $\{(t_i - p_j) / \|t_i - p_j\|_2\}_{i,j \in [n_l] \times [n_s]}$, where a constant fraction of these observations are arbitrarily corrupted, find $\{t_i\}_{i \in [n_ll]}$ and $\{p_j\}_{j \in [n_s]}$ up to a global translation and scale. We study the recently introduced ShapeFit algorithm as a method for solving this bipartite location recovery problem. In this case, ShapeFit consists of a simple convex program over $d(n_l + n_s)$ real variables. We prove that this program recovers a set of $n_l+n_s$ i.i.d. Gaussian locations exactly and with high probability if the observations are given by a bipartite Erd\H{o}s-R\'{e}nyi graph, $d$ is large enough, and provided that at most a constant fraction of observations involving any particular location are adversarially corrupted. This recovery theorem is based on a set of deterministic conditions that we prove are sufficient for exact recovery. Finally, we propose a modified pipeline for the Structure for Motion problem, based on this bipartite location recovery problem.

##### Abstract (translated by Google)
在\ mathbb {R} ^ d $中设置$ t_1，\ ldots，t_ {n_l} \和\ mathbb {R} ^ d $中的$ p_1，\ ldots，p_ {n_s} \并考虑双方位置恢复问题：给定成对方向观测值的一个子集，其中一个常数分数观测值被任意地破坏，在[n_ll]} $和$ \ {p_j \} _ {j \ in [n_s]} $中找到$ \ {t_i \} _ {i \我们研究最近推出的ShapeFit算法作为解决这个双方位置恢复问题的方法。在这种情况下，ShapeFit由$ d（n_l + n_s）$ real变量的简单凸面程序组成。我们证明这个程序恢复了一组$ n_l + n_s $ i.i.d.如果观测值是由二部分Erd \ H {o} sR \ {e} nyi图表$ d $足够大，并且最多提供了涉及任何特定位置被敌对破坏。这个恢复定理是基于一组确定性条件，我们证明是足够的准确恢复。最后，我们基于这个双边位置恢复问题，提出了一种用于运动结构问题的修改管道。

##### URL
[https://arxiv.org/abs/1509.05064](https://arxiv.org/abs/1509.05064)

##### PDF
[https://arxiv.org/pdf/1509.05064](https://arxiv.org/pdf/1509.05064)

