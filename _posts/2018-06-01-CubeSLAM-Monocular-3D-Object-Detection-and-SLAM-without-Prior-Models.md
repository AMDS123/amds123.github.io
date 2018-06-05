---
layout: post
title: "CubeSLAM: Monocular 3D Object Detection and SLAM without Prior Models"
date: 2018-06-01 22:44:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection SLAM
author: Shichao Yang, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for single image 3D cuboid object detection and multi-view object SLAM without prior object model, and demonstrate that the two aspects can benefit each other. For 3D detection, we generate high quality cuboid proposals from 2D bounding boxes and vanishing points sampling. The proposals are further scored and selected to align with image edges. Experiments on SUN RGBD and KITTI shows the efficiency and accuracy over existing approaches. Then in the second part, multi-view bundle adjustment with novel measurement functions is proposed to jointly optimize camera poses, objects and points, utilizing single view detection results. Objects can provide more geometric constraints and scale consistency compared to points. On the collected and public TUM and KITTI odometry datasets, we achieve better pose estimation accuracy over the state-of-the-art monocular SLAM while also improve the 3D object detection accuracy at the same time.

##### Abstract (translated by Google)
我们提出了一种单一图像3D立方体对象检测和多视图对象SLAM的方法，没有先验对象模型，并且证明这两个方面可以互相利用。对于3D检测，我们从2D边界框和消失点采样生成高质量立方体提案。这些提议被进一步评分和选择以与图像边缘对齐。 SUN RGBD和KITTI的实验显示了现有方法的效率和准确性。然后在第二部分中，利用单视图检测结果，提出了利用新型测量函数进行多视图束调整，对摄像机的姿态，对象和点进行联合优化。与点相比，对象可以提供更多的几何约束和比例一致性。在收集的公共TUM和KITTI测距数据集上，我们实现了比现有单眼SLAM更好的姿态估计精度，同时还提高了3D物体检测精度。

##### URL
[http://arxiv.org/abs/1806.00557](http://arxiv.org/abs/1806.00557)

##### PDF
[http://arxiv.org/pdf/1806.00557](http://arxiv.org/pdf/1806.00557)

