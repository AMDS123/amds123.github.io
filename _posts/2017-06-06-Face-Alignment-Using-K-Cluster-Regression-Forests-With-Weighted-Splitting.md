---
layout: post
title: "Face Alignment Using K-Cluster Regression Forests With Weighted Splitting"
date: 2017-06-06 15:42:12
categories: arXiv_CV
tags: arXiv_CV Face
author: Marek Kowalski, Jacek Naruniec
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a face alignment pipeline based on two novel methods: weighted splitting for K-cluster Regression Forests and 3D Affine Pose Regression for face shape initialization. Our face alignment method is based on the Local Binary Feature framework, where instead of standard regression forests and pixel difference features used in the original method, we use our K-cluster Regression Forests with Weighted Splitting (KRFWS) and Pyramid HOG features. We also use KRFWS to perform Affine Pose Regression (APR) and 3D-Affine Pose Regression (3D-APR), which intend to improve the face shape initialization. APR applies a rigid 2D transform to the initial face shape that compensates for inaccuracy in the initial face location, size and in-plane rotation. 3D-APR estimates the parameters of a 3D transform that additionally compensates for out-of-plane rotation. The resulting pipeline, consisting of APR and 3D-APR followed by face alignment, shows an improvement of 20% over standard LBF on the challenging IBUG dataset, and state-of-theart accuracy on the entire 300-W dataset.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种基于两种新方法的面对齐管道：K聚类回归森林的加权分裂和3D脸部形状初始化的3D仿射姿态回归。我们的人脸对齐方法是基于局部二值特征框架，而不是原始方法中使用的标准回归森林和像素差异特征，我们使用我们的具有加权分割的K-聚类回归森林（KRFWS）和金字塔HOG特征。我们还使用KRFWS来执行仿射姿态回归（APR）和3D仿射姿态回归（3D-APR），其旨在改善面形初始化。 APR将刚性2D变换应用于初始人脸形状，以补偿初始人脸位置，大小和面内旋转的不准确性。 3D-APR估计额外补偿平面外旋转的3D变换的参数。由APR和3D-APR构成的流水线随后进行面对齐，在具有挑战性的IBUG数据集上显示比标准LBF提高20％，并在整个300-W数据集上显示出现有的精度。

##### URL
[https://arxiv.org/abs/1706.01820](https://arxiv.org/abs/1706.01820)

##### PDF
[https://arxiv.org/pdf/1706.01820](https://arxiv.org/pdf/1706.01820)

