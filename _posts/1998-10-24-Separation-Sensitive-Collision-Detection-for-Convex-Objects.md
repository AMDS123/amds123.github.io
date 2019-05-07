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


##### URL
[https://arxiv.org/abs/cs/9809035](https://arxiv.org/abs/cs/9809035)

##### PDF
[https://arxiv.org/pdf/cs/9809035](https://arxiv.org/pdf/cs/9809035)

