---
layout: post
title: "Separation-Sensitive Collision Detection for Convex Objects"
date: 1998-10-24 21:51:28
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jeff Erickson, Leonidas J. Guibas, Jorge Stolfi, Li Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a class of new kinetic data structures for collision detection between moving convex polytopes; the performance of these structures is sensitive to the separation of the polytopes during their motion. For two convex polygons in the plane, let $D$ be the maximum diameter of the polygons, and let $s$ be the minimum distance between them during their motion. Our separation certificate changes $O(\log(D/s))$ times when the relative motion of the two polygons is a translation along a straight line or convex curve, $O(\sqrt{D/s})$ for translation along an algebraic trajectory, and $O(D/s)$ for algebraic rigid motion (translation and rotation). Each certificate update is performed in $O(\log(D/s))$ time. Variants of these data structures are also shown that exhibit \emph{hysteresis}---after a separation certificate fails, the new certificate cannot fail again until the objects have moved by some constant fraction of their current separation. We can then bound the number of events by the combinatorial size of a certain cover of the motion path by balls.

##### Abstract (translated by Google)
我们为移动凸多面体之间的碰撞检测开发了一类新的动力学数据结构;这些结构的性能对运动过程中多面体的分离非常敏感。对于平面中的两个凸多边形，令$ D $为多边形的最大直径，并且让$ s $为它们在运动期间的最小距离。当两个多边形的相对运动是沿直线或凸曲线的平移时，我们的分离证书改变$ O（\ log（D / s））$次，$ O（\ sqrt {D / s}）$用于平移沿代数轨迹运动，代数刚体运动（平移和旋转）为$ O（D / s）$。每个证书更新在$ O（\ log（D / s））$ time中执行。这些数据结构的变体也被显示出来，在分离证书失败之后，新的证书不会再次失败，直到对象已经移动了它们当前分离的一些不变的部分为止。然后，我们可以通过球的运动路径的某个封面的组合大小来限制事件的数量。

##### URL
[https://arxiv.org/abs/cs/9809035](https://arxiv.org/abs/cs/9809035)

