---
layout: post
title: "Fast and Accurate Intrinsic Symmetry Detection"
date: 2018-07-26 14:18:36
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Rajendra Nagar, Shanmuganathan Raman
mathjax: true
---

* content
{:toc}

##### Abstract
In computer vision and graphics, various types of symmetries are extensively studied since symmetry present in objects is a fundamental cue for understanding the shape and the structure of objects. In this work, we detect the intrinsic reflective symmetry in triangle meshes where we have to find the intrinsically symmetric point for each point of the shape. We establish correspondences between functions defined on the shapes by extending the functional map framework and then recover the point-to-point correspondences. Previous approaches using the functional map for this task find the functional correspondences matrix by solving a non-linear optimization problem which makes them slow. In this work, we propose a closed form solution for this matrix which makes our approach faster. We find the closed-form solution based on our following results. If the given shape is intrinsically symmetric, then the shortest length geodesic between two intrinsically symmetric points is also intrinsically symmetric. If an eigenfunction of the Laplace-Beltrami operator for the given shape is an even (odd) function, then its restriction on the shortest length geodesic between two intrinsically symmetric points is also an even (odd) function. The sign of a low-frequency eigenfunction is the same on the neighboring points. Our method is invariant to the ordering of the eigenfunctions and has the least time complexity. We achieve the best performance on the SCAPE dataset and comparable performance with the state-of-the-art methods on the TOSCA dataset.

##### Abstract (translated by Google)
在计算机视觉和图形中，广泛研究了各种类型的对称性，因为对象中存在的对称性是理解对象的形状和结构的基本线索。在这项工作中，我们检测三角形网格中的内在反射对称性，我们必须找到形状的每个点的固有对称点。我们通过扩展功能映射框架建立在形状上定义的函数之间的对应关系，然后恢复点对点的对应关系。以前使用功能映射进行此任务的方法通过解决使其慢的非线性优化问题来找到函数对应矩阵。在这项工作中，我们为这个矩阵提出了一个封闭形式的解决方案，使我们的方法更快。我们根据以下结果找到了封闭形式的解决方案。如果给定的形状本质上是对称的，那么两个本征对称点之间的最短长度测地线也是本质上对称的。如果对于给定形状的拉普拉斯 - 贝尔特拉米算子的本征函数是偶数（奇数）函数，则其对两个本征对称点之间的最短长度测地线的限制也是偶数（奇数）函数。低频特征函数的符号在相邻点上是相同的。我们的方法对于特征函数的排序是不变的，并且具有最小的时间复杂度。我们在SCAPE数据集上实现了最佳性能，并且与TOSCA数据集上的最新方法具有可比性。

##### URL
[http://arxiv.org/abs/1807.10162](http://arxiv.org/abs/1807.10162)

##### PDF
[http://arxiv.org/pdf/1807.10162](http://arxiv.org/pdf/1807.10162)

