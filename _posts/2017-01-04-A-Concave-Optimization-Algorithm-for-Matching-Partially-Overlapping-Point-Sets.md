---
layout: post
title: "A Concave Optimization Algorithm for Matching Partially Overlapping Point Sets"
date: 2017-01-04 10:28:10
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Wei Lian, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Point matching refers to the process of finding spatial transformation and correspondences between two sets of points. In this paper, we focus on the case that there is only partial overlap between two point sets. Following the approach of the robust point matching method, we model point matching as a mixed linear assignment-least square problem and show that after eliminating the transformation variable, the resulting problem of minimization with respect to point correspondence is a concave optimization problem. Furthermore, this problem has the property that the objective function can be converted into a form with few nonlinear terms via a linear transformation. Based on these properties, we employ the branch-and-bound (BnB) algorithm to optimize the resulting problem where the dimension of the search space is small. To further improve efficiency of the BnB algorithm where computation of the lower bound is the bottleneck, we propose a new lower bounding scheme which has a k-cardinality linear assignment formulation and can be efficiently solved. Experimental results show that the proposed algorithm outperforms state-of-the-art methods in terms of robustness to disturbances and point matching accuracy.

##### Abstract (translated by Google)
点匹配是指找出两组点之间的空间变换和对应关系的过程。在本文中，我们重点关注两点集之间只有部分重叠的情况。根据鲁棒点匹配方法，将点匹配建模为混合线性赋值最小二乘问题，并证明在消除变换变量后，最终导致的点对应问题是凹优化问题。此外，该问题具有通过线性变换将目标函数转化为一个非线性项较少的形式的性质。基于这些性质，我们采用分枝定界（BnB）算法来优化搜索空间维度小的结果问题。为了进一步提高BnB算法的效率，其中下界的计算是瓶颈，我们提出了一个新的下界方案，它有一个k-基数线性分配的表达式，可以有效地解决。实验结果表明，该算法在干扰鲁棒性和点匹配精度方面优于现有技术。

##### URL
[https://arxiv.org/abs/1701.00951](https://arxiv.org/abs/1701.00951)

##### PDF
[https://arxiv.org/pdf/1701.00951](https://arxiv.org/pdf/1701.00951)

