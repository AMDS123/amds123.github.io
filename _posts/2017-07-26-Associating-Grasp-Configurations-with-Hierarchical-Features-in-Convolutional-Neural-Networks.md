---
layout: post
title: "Associating Grasp Configurations with Hierarchical Features in Convolutional Neural Networks"
date: 2017-07-26 00:41:01
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Relation
author: Li Yang Ku, Erik Learned-Miller, Rod Grupen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we provide a solution for posturing the anthropomorphic Robonaut-2 hand and arm for grasping based on visual information. A mapping from visual features extracted from a convolutional neural network (CNN) to grasp points is learned. We demonstrate that a CNN pre-trained for image classification can be applied to a grasping task based on a small set of grasping examples. Our approach takes advantage of the hierarchical nature of the CNN by identifying features that capture the hierarchical support relations between filters in different CNN layers and locating their 3D positions by tracing activations backwards in the CNN. When this backward trace terminates in the RGB-D image, important manipulable structures are thereby localized. These features that reside in different layers of the CNN are then associated with controllers that engage different kinematic subchains in the hand/arm system for grasping. A grasping dataset is collected using demonstrated hand/object relationships for Robonaut-2 to evaluate the proposed approach in terms of the precision of the resulting preshape postures. We demonstrate that this approach outperforms baseline approaches in cluttered scenarios on the grasping dataset and a point cloud based approach on a grasping task using Robonaut-2.

##### Abstract (translated by Google)
在这项工作中，我们提供了一个解决方案，以摆放基于视觉信息的拟人Robonaut-2手和手臂。学习从卷积神经网络（CNN）提取的视觉特征到抓点的映射。我们证明，一个CNN预先训练的图像分类可以应用于一个抓取任务的基础上的一小部分抓住的例子。我们的方法通过识别捕获不同CNN层中的滤波器之间的分级支持关系的特征，并通过在CNN中向后追踪激活来定位它们的3D位置，来利用CNN的分层特性。当这个后向轨迹终止于RGB-D图像时，重要的可操纵结构因此被局部化。这些驻留在CNN的不同层中的特征然后与控制器相关联，该控制器接合手/臂系统中的不同运动子链进行抓握。使用Robonaut-2展示的手/对象关系收集抓取数据集，以根据所得预成形姿势的精确度来评估所提出的方法。我们证明，这种方法胜过了基线方法在抓取数据集上的混乱场景和基于点云的方法上使用Robonaut-2抓住任务。

##### URL
[https://arxiv.org/abs/1609.03947](https://arxiv.org/abs/1609.03947)

##### PDF
[https://arxiv.org/pdf/1609.03947](https://arxiv.org/pdf/1609.03947)

