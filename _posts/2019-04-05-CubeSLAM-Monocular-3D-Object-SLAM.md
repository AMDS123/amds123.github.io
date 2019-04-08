---
layout: post
title: "CubeSLAM: Monocular 3D Object SLAM"
date: 2019-04-05 06:05:44
categories: arXiv_RO
tags: arXiv_RO Object_Detection Pose_Estimation Detection SLAM
author: Shichao Yang, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for single image 3D cuboid object detection and multi-view object SLAM in both static and dynamic environments, and demonstrate that the two parts can improve each other. Firstly for single image object detection, we generate high-quality cuboid proposals from 2D bounding boxes and vanishing points sampling. The proposals are further scored and selected based on the alignment with image edges. Secondly, multi-view bundle adjustment with new object measurements is proposed to jointly optimize poses of cameras, objects and points. Objects can provide long-range geometric and scale constraints to improve camera pose estimation and reduce monocular drift. Instead of treating dynamic regions as outliers, we utilize object representation and motion model constraints to improve the camera pose estimation. The 3D detection experiments on SUN RGBD and KITTI show better accuracy and robustness over existing approaches. On the public TUM, KITTI odometry and our own collected datasets, our SLAM method achieves the state-of-the-art monocular camera pose estimation and at the same time, improves the 3D object detection accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00557](http://arxiv.org/abs/1806.00557)

##### PDF
[http://arxiv.org/pdf/1806.00557](http://arxiv.org/pdf/1806.00557)

