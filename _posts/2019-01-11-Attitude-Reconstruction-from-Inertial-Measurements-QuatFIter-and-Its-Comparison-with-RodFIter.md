---
layout: post
title: "Attitude Reconstruction from Inertial Measurements: QuatFIter and Its Comparison with RodFIter"
date: 2019-01-11 03:38:06
categories: arXiv_RO
tags: arXiv_RO
author: Yuanxin Wu, Gongmin Yan
mathjax: true
---

* content
{:toc}

##### Abstract
RodFIter is a promising method of attitude reconstruction from inertial measurements based on the functional iterative integration of Rodrigues vector. The Rodrigues vector is used to encode the attitude in place of the popular rotation vector because it has a polynomial-like rate equation and could be cast into theoretically sound and exact integration. This paper further applies the approach of RodFIter to the unity-norm quaternion for attitude reconstruction, named QuatFIter, and shows that it is identical to the previous Picard-type quaternion method. The Chebyshev polynomial approximation and truncation techniques from the RodFIter are exploited to speed up its implementation. Numerical results demonstrate that the QuatFIter is comparable in accuracy to the RodFIter, although its convergence rate is relatively slower with respect to the number of iterations. Notably, the QuatFIter has about two times better computational efficiency, thanks to the linear quaternion kinematic equation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03468](http://arxiv.org/abs/1901.03468)

##### PDF
[http://arxiv.org/pdf/1901.03468](http://arxiv.org/pdf/1901.03468)

