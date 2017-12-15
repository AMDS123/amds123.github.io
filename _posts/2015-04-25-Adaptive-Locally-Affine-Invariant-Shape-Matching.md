---
layout: post
title: "Adaptive Locally Affine-Invariant Shape Matching"
date: 2015-04-25 12:01:30
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Smit Marvaniya, Raj Gupta, Anurag Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
Matching deformable objects using their shapes is an important problem in computer vision since shape is perhaps the most distinguishable characteristic of an object. The problem is difficult due to many factors such as intra-class variations, local deformations, articulations, viewpoint changes and missed and extraneous contour portions due to errors in shape extraction. While small local deformations has been handled in the literature by allowing some leeway in the matching of individual contour points via methods such as Chamfer distance and Hausdorff distance, handling more severe deformations and articulations has been done by applying local geometric corrections such as similarity or affine. However, determining which portions of the shape should be used for the geometric corrections is very hard, although some methods have been tried. In this paper, we address this problem by an efficient search for the group of contour segments to be clustered together for a geometric correction using Dynamic Programming by essentially searching for the segmentations of two shapes that lead to the best matching between them. At the same time, we allow portions of the contours to remain unmatched to handle missing and extraneous contour portions. Experiments indicate that our method outperforms other algorithms, especially when the shapes to be matched are more complex.

##### Abstract (translated by Google)
使用形状匹配可变形物体是计算机视觉中的一个重要问题，因为形状可能是物体最明显的特征。由于诸如类内变化，局部变形，关节，视点变化以及由于形状提取中的误差而引起的遗漏和无关的轮廓部分等诸多因素，问题是困难的。尽管在文献中通过允许通过诸如倒角距离和豪斯多夫距离的方法在各个轮廓点的匹配中存在一些余地，已经处理了较小的局部变形，但是通过应用局部几何校正例如相似性或仿射来处理更严重的变形和关节。然而，尽管已经尝试了一些方法，但是确定哪些部分的形状应该用于几何校正是非常困难的。在本文中，我们解决了这个问题，通过有效地搜索轮廓段的一组来聚集在一起，使用动态规划进行几何校正，通过基本上搜索两个形状的分割，导致它们之间的最佳匹配。同时，我们允许部分轮廓保持不匹配，以处理缺失和无关的轮廓部分。实验表明，我们的方法胜过其他算法，特别是当要匹配的形状更复杂。

##### URL
[https://arxiv.org/abs/1504.06719](https://arxiv.org/abs/1504.06719)

##### PDF
[https://arxiv.org/pdf/1504.06719](https://arxiv.org/pdf/1504.06719)

