---
layout: post
title: "PointIT: A Fast Tracking Framework Based on 3D Instance Segmentation"
date: 2019-02-18 02:39:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking
author: Yuan Wang, Yang Yu, Ming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently most popular tracking frameworks focus on 2D image sequences. They seldom track the 3D object in point clouds. In this paper, we propose PointIT, a fast, simple tracking method based on 3D on-road instance segmentation. Firstly, we transform 3D LiDAR data into the spherical image with the size of 64 x 512 x 4 and feed it into instance segment model to get the predicted instance mask for each class. Then we use MobileNet as our primary encoder instead of the original ResNet to reduce the computational complexity. Finally, we extend the Sort algorithm with this instance framework to realize tracking in the 3D LiDAR point cloud data. The model is trained on the spherical images dataset with the corresponding instance label masks which are provided by KITTI 3D Object Track dataset. According to the experiment results, our network can achieve on Average Precision (AP) of 0.617 and the performance of multi-tracking task has also been improved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06379](http://arxiv.org/abs/1902.06379)

##### PDF
[http://arxiv.org/pdf/1902.06379](http://arxiv.org/pdf/1902.06379)

