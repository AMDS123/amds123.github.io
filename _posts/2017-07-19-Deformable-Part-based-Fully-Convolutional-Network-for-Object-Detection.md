---
layout: post
title: "Deformable Part-based Fully Convolutional Network for Object Detection"
date: 2017-07-19 16:03:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Taylor Mordan, Nicolas Thome, Matthieu Cord, Gilles Henaff
mathjax: true
---

* content
{:toc}

##### Abstract
Existing region-based object detectors are limited to regions with fixed box geometry to represent objects, even if those are highly non-rectangular. In this paper we introduce DP-FCN, a deep model for object detection which explicitly adapts to shapes of objects with deformable parts. Without additional annotations, it learns to focus on discriminative elements and to align them, and simultaneously brings more invariance for classification and geometric information to refine localization. DP-FCN is composed of three main modules: a Fully Convolutional Network to efficiently maintain spatial resolution, a deformable part-based RoI pooling layer to optimize positions of parts and build invariance, and a deformation-aware localization module explicitly exploiting displacements of parts to improve accuracy of bounding box regression. We experimentally validate our model and show significant gains. DP-FCN achieves state-of-the-art performances of 83.1% and 80.9% on PASCAL VOC 2007 and 2012 with VOC data only.

##### Abstract (translated by Google)
现有的基于区域的物体检测器仅限于具有固定盒子几何形状的区域来表示物体，即使这些区域是高度非矩形的。在本文中，我们介绍了DP-FCN，一个深度的物体检测模型，明确适应物体的形状与可变形的部分。如果没有额外的注释，它会学习将重点放在判别性元素上并对齐它们，同时为分类和几何信息带来更多的不变性以优化本地化。 DP-FCN由三个主要模块组成：一个用于高效地维持空间分辨率的全卷积网络，一个基于可变形部件的RoI池层以优化部件的位置和建立不变性，以及一个形变感知定位模块，明确地利用部件的位移提高边界框回归的准确性。我们通过实验验证了我们的模型并显示出显着的收益。 DP-FCN在2007年和2012年的PASCAL VOC上仅达到了VOC数据的83.1％和80.9％的最新性能。

##### URL
[https://arxiv.org/abs/1707.06175](https://arxiv.org/abs/1707.06175)

##### PDF
[https://arxiv.org/pdf/1707.06175](https://arxiv.org/pdf/1707.06175)

