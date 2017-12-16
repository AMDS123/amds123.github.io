---
layout: post
title: "Learning a 3D descriptor for cross-source point cloud registration from synthetic data"
date: 2017-08-24 22:38:02
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Relation
author: Xiaoshui Huang
mathjax: true
---

* content
{:toc}

##### Abstract
As the development of 3D sensors, registration of 3D data (e.g. point cloud) coming from different kind of sensor is dispensable and shows great demanding. However, point cloud registration between different sensors is challenging because of the variant of density, missing data, different viewpoint, noise and outliers, and geometric transformation. In this paper, we propose a method to learn a 3D descriptor for finding the correspondent relations between these challenging point clouds. To train the deep learning framework, we use synthetic 3D point cloud as input. Starting from synthetic dataset, we use region-based sampling method to select reasonable, large and diverse training samples from synthetic samples. Then, we use data augmentation to extend our network be robust to rotation transformation. We focus our work on more general cases that point clouds coming from different sensors, named cross-source point cloud. The experiments show that our descriptor is not only able to generalize to new scenes, but also generalize to different sensors. The results demonstrate that the proposed method successfully aligns two 3D cross-source point clouds which outperforms state-of-the-art method.

##### Abstract (translated by Google)
随着3D传感器的发展，来自不同类型的传感器的3D数据（例如，点云）的配准是可有可无的，并且显示出高度的要求。然而，不同传感器之间的点云配准由于密度的变化，缺失的数据，不同的视点，噪声和异常值以及几何变换而具有挑战性。在本文中，我们提出了一种方法来学习一个三维描述符，以找到这些具有挑战性的点云之间的对应关系。为了训练深度学习框架，我们使用合成三维点云作为输入。从合成数据集开始，我们使用基于区域的抽样方法从合成样本中选择合理的，大量的和多样化的训练样本。然后，我们使用数据增强来扩展我们的网络对旋转变换的鲁棒性。我们将工作重点放在更多一般情况上，指出来自不同传感器的云，称为交叉源点云。实验表明，我们的描述符不仅能够推广到新的场景，而且推广到不同的传感器。结果表明，所提出的方法成功地对齐了两个三维交叉源点云，其性能优于最先进的方法。

##### URL
[https://arxiv.org/abs/1708.08997](https://arxiv.org/abs/1708.08997)

##### PDF
[https://arxiv.org/pdf/1708.08997](https://arxiv.org/pdf/1708.08997)

