---
layout: post
title: "SqueezeSeg: Convolutional Neural Nets with Recurrent CRF for Real-Time Road-Object Segmentation from 3D LiDAR Point Cloud"
date: 2017-10-19 23:03:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Bichen Wu, Alvin Wan, Xiangyu Yue, Kurt Keutzer
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address semantic segmentation of road-objects from 3D LiDAR point clouds. In particular, we wish to detect and categorize instances of interest, such as cars, pedestrians and cyclists. We formulate this problem as a point- wise classification problem, and propose an end-to-end pipeline called SqueezeSeg based on convolutional neural networks (CNN): the CNN takes a transformed LiDAR point cloud as input and directly outputs a point-wise label map, which is then refined by a conditional random field (CRF) implemented as a recurrent layer. Instance-level labels are then obtained by conventional clustering algorithms. Our CNN model is trained on LiDAR point clouds from the KITTI dataset, and our point-wise segmentation labels are derived from 3D bounding boxes from KITTI. To obtain extra training data, we built a LiDAR simulator into Grand Theft Auto V (GTA-V), a popular video game, to synthesize large amounts of realistic training data. Our experiments show that SqueezeSeg achieves high accuracy with astonishingly fast and stable runtime (8.7 ms per frame), highly desirable for autonomous driving applications. Furthermore, additionally training on synthesized data boosts validation accuracy on real-world data. Our source code and synthesized data will be open-sourced.

##### Abstract (translated by Google)
在本文中，我们讨论了三维LiDAR点云对道路物体的语义分割。我们特别希望检测和分类感兴趣的事件，例如汽车，行人和骑自行车者。我们将这个问题作为一个逐点分类问题来提出，并且提出了一个基于卷积神经网络（CNN）的称为SqueezeSeg的端到端流水线：CNN将一个转换后的LiDAR点云作为输入，并直接输出一个点向标签map，然后通过作为递归层实现的条件随机场（CRF）进行细化。然后通过传统的聚类算法获得实例级标签。我们的CNN模型是从KITTI数据集中对LiDAR点云进行训练的，而我们的点分割标签则是从KITTI的三维边界框中得到的。为了获得额外的训练数据，我们建立了一个流行的视频游戏“侠盗猎车手5”（GTA-V）的LiDAR模拟器来合成大量逼真的训练数据。我们的实验表明，SqueezeSeg具有惊人的快速和稳定运行时间（每帧8.7毫秒），实现了高精度，非常适合自主驾驶应用。此外，对合成数据进行额外培训可提高真实数据的验证准确度。我们的源代码和综合数据将是开源的。

##### URL
[https://arxiv.org/abs/1710.07368](https://arxiv.org/abs/1710.07368)

##### PDF
[https://arxiv.org/pdf/1710.07368](https://arxiv.org/pdf/1710.07368)

