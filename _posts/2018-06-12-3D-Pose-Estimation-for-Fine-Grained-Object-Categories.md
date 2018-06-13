---
layout: post
title: "3D Pose Estimation for Fine-Grained Object Categories"
date: 2018-06-12 03:44:54
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Recognition
author: Yaming Wang, Xiao Tan, Yi Yang, Xiao Liu, Errui Ding, Feng Zhou, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Existing object pose estimation datasets are related to generic object types and there is so far no dataset for fine-grained object categories. In this work, we introduce a new large dataset to benchmark pose estimation for fine-grained objects, thanks to the availability of both 2D and 3D fine-grained data recently. Specifically, we augment two popular fine-grained recognition datasets (StanfordCars and CompCars) by finding a fine-grained 3D CAD model for each sub-category and manually annotating each object in images with 3D pose. We show that, with enough training data, a full perspective model with continuous parameters can be estimated using 2D appearance information alone. We achieve this via a framework based on Faster/Mask R-CNN. This goes beyond previous works on category-level pose estimation, which only estimate discrete/continuous viewpoint angles or recover rotation matrices often with the help of key points. Furthermore, with fine-grained 3D models available, we incorporate a novel 3D representation named as {\em location field} into the CNN-based pose estimation framework to further improve the performance.

##### Abstract (translated by Google)
现有的对象姿态估计数据集与通用对象类型相关，并且目前还没有用于细粒度对象类别的数据集。在这项工作中，我们引入了一个新的大型数据集来对基于细粒度物体的姿态估计进行基准测试，这要归功于最近可用的2D和3D细粒度数据。具体而言，我们通过为每个子类别找到细粒度的3D CAD模型并用3D姿势手动注释图像中的每个对象来增强两种流行的细粒度识别数据集（StanfordCars和CompCars）。我们证明，只要有足够的训练数据，就可以仅使用2D外观信息来估计具有连续参数的完整透视模型。我们通过基于Faster / Mask R-CNN的框架来实现这一目标。这超出了之前关于类别级别姿态估计的研究，它只是通过关键点的帮助来估计离散/连续视角或恢复旋转矩阵。此外，通过使用细粒度的3D模型，我们在基于CNN的姿态估计框架中引入了名为{\ em location field}的新颖3D表示形式，以进一步提高性能。

##### URL
[http://arxiv.org/abs/1806.04314](http://arxiv.org/abs/1806.04314)

##### PDF
[http://arxiv.org/pdf/1806.04314](http://arxiv.org/pdf/1806.04314)

