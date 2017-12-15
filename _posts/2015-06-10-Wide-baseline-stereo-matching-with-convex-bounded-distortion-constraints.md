---
layout: post
title: "Wide baseline stereo matching with convex bounded-distortion constraints"
date: 2015-06-10 13:48:34
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Meirav Galun, Tal Amir, Tal Hassner, Ronen Basri, Yaron Lipman
mathjax: true
---

* content
{:toc}

##### Abstract
Finding correspondences in wide baseline setups is a challenging problem. Existing approaches have focused largely on developing better feature descriptors for correspondence and on accurate recovery of epipolar line constraints. This paper focuses on the challenging problem of finding correspondences once approximate epipolar constraints are given. We introduce a novel method that integrates a deformation model. Specifically, we formulate the problem as finding the largest number of corresponding points related by a bounded distortion map that obeys the given epipolar constraints. We show that, while the set of bounded distortion maps is not convex, the subset of maps that obey the epipolar line constraints is convex, allowing us to introduce an efficient algorithm for matching. We further utilize a robust cost function for matching and employ majorization-minimization for its optimization. Our experiments indicate that our method finds significantly more accurate maps than existing approaches.

##### Abstract (translated by Google)
在宽基线设置中查找对应关系是一个具有挑战性的问题。现有的方法主要集中在开发更好的函数描述符和精确恢复核线约束。本文重点讨论一旦给出近似的极线约束就找到对应关系的挑战性问题。我们介绍一种整合变形模型的新方法。具体而言，我们制定的问题是找到与有限的失真图相关的最大数量的相应点，服从给定的极线约束。我们证明，尽管有界变形映射的集合不是凸的，但服从极线约束的映射子集是凸的，这使我们可以引入一个有效的匹配算法。我们进一步利用一个强大的成本函数进行匹配，并采用优化的最小化。我们的实验表明，我们的方法发现比现有的方法显着更准确的地图。

##### URL
[https://arxiv.org/abs/1506.03301](https://arxiv.org/abs/1506.03301)

##### PDF
[https://arxiv.org/pdf/1506.03301](https://arxiv.org/pdf/1506.03301)

