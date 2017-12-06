---
layout: post
title: "3D Object Proposals using Stereo Imagery for Accurate Object Class Detection"
date: 2017-04-25 07:58:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xiaozhi Chen, Kaustav Kundu, Yukun Zhu, Huimin Ma, Sanja Fidler, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to perform 3D object detection in the context of autonomous driving. Our method first aims at generating a set of high-quality 3D object proposals by exploiting stereo imagery. We formulate the problem as minimizing an energy function that encodes object size priors, placement of objects on the ground plane as well as several depth informed features that reason about free space, point cloud densities and distance to the ground. We then exploit a CNN on top of these proposals to perform object detection. In particular, we employ a convolutional neural net (CNN) that exploits context and depth information to jointly regress to 3D bounding box coordinates and object pose. Our experiments show significant performance gains over existing RGB and RGB-D object proposal methods on the challenging KITTI benchmark. When combined with the CNN, our approach outperforms all existing results in object detection and orientation estimation tasks for all three KITTI object classes. Furthermore, we experiment also with the setting where LIDAR information is available, and show that using both LIDAR and stereo leads to the best result.

##### Abstract (translated by Google)
本文的目标是在自主驾驶环境下进行三维物体检测。我们的方法首先旨在通过利用立体图像来生成一组高质量的3D对象提议。我们将问题描述为最小化一个能量函数，这个函数能够编码物体大小的先验，物体在地平面上的位置，以及几个深度信息特征，这些特征可以解释自由空间，点云密度和到地面的距离。然后，我们利用这些提议之上的CNN来执行对象检测。具体而言，我们使用卷积神经网络（CNN），利用上下文信息和深度信息共同回归到三维边界框坐标和物体姿态。我们的实验显示，在具有挑战性的KITTI基准测试中，与现有的RGB和RGB-D对象提议方法相比，性能显着提高当与CNN相结合时，我们的方法胜过所有三个KITTI对象类的对象检测和方向估计任务中的所有现有结果。此外，我们还试验LIDAR信息可用的设置，并显示使用激光雷达和立体声导致最佳结果。

##### URL
[https://arxiv.org/abs/1608.07711](https://arxiv.org/abs/1608.07711)

