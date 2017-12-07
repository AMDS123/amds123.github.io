---
layout: post
title: "A Joint 3D-2D based Method for Free Space Detection on Roads"
date: 2017-12-06 09:50:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Suvam Patra, Pranjal Maheshwari, Shashank Yadav, Chetan Arora, Subhashis Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of road segmentation and free space detection in the context of autonomous driving. Traditional methods either use 3D cues such as point clouds obtained from LIDAR, RADAR or stereo cameras or 2D cues such as lane markings, road boundaries, and object detection. Typical 3D point clouds do not have enough resolution to detect fine differences in heights such as between road and pavement. Similarly, image-based cues fail when encountering uneven road textures such as due to shadows, potholes, lane markings or road restoration. Exploiting the rapid advances made in recent years in 2D image segmentation as well as SLAM (Simultaneous Localization and Mapping) problems, we propose a novel free road space detection technique based on the combination of cues from deep convolutional neural networks (CNN) and sparse depth from monocular SLAM. In particular, we use the CNN based road segmentation from 2D images and plane/box fitting on sparse depth data obtained from SLAM as priors to formulate an energy minimization using the conditional random field (CRF) for road pixels classification. While the CNN learns the road texture, the depth information tries to fill in the details for which texture-based classification fails. Finally, we use the obtained road segmentation with the 3D depth data from monocular SLAM to detect the free space for the navigation purposes. Our experiments on KITTI odometry dataset, Camvid dataset as well as videos captured by us validate the superiority of the proposed approach over the state of the art.

##### Abstract (translated by Google)
在本文中，我们解决了自主驾驶环境下的道路分割和自由空间探测问题。传统的方法要么使用3D提示，如从激光雷达，雷达或立体相机获得的点云或2D线索，如车道标记，道路边界和物体检测。典型的3D点云没有足够的分辨率来检测高度上的细微差异，例如道路和路面之间的差异。类似地，基于图像的线索在遇到不平整的道路纹理（例如由于阴影，坑洼，车道标记或道路修复）时会失败。利用近年来在二维图像分割以及SLAM（同时定位和映射）问题上取得的快速进展，提出了一种基于深度卷积神经网络（CNN）和稀疏深度从单眼SLAM。特别地，我们使用基于CNN的二维图像道路分割和从SLAM获得的稀疏深度数据的平面/盒拟合作为先验，以使用用于道路像素分类的条件随机场（CRF）制定能量最小化。当CNN学习道路纹理时，深度信息试图填充基于纹理的分类失败的细节。最后，利用单眼SLAM得到的三维深度数据得到的道路分割，进行导航目的的自由空间检测。我们在KITTI odometry数据集，Camvid数据集以及我们拍摄的视频上进行的实验验证了所提出的方法相对于现有技术的优越性。

##### URL
[http://arxiv.org/abs/1711.02144](http://arxiv.org/abs/1711.02144)

##### PDF
[http://arxiv.org/pdf/1711.02144](http://arxiv.org/pdf/1711.02144)

