---
layout: post
title: "Hallucinating Dense Optical Flow from Sparse Lidar for Autonomous Vehicles"
date: 2018-08-30 22:54:44
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Victor Vaquero, Alberto Sanfeliu, Francesc Moreno-Noguer
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel approach to estimate dense optical flow from sparse lidar data acquired on an autonomous vehicle. This is intended to be used as a drop-in replacement of any image-based optical flow system when images are not reliable due to e.g. adverse weather conditions or at night. In order to infer high resolution 2D flows from discrete range data we devise a three-block architecture of multiscale filters that combines multiple intermediate objectives, both in the lidar and image domain. To train this network we introduce a dataset with approximately 20K lidar samples of the Kitti dataset which we have augmented with a pseudo ground-truth image-based optical flow computed using FlowNet2. We demonstrate the effectiveness of our approach on Kitti, and show that despite using the low-resolution and sparse measurements of the lidar, we can regress dense optical flow maps which are at par with those estimated with image-based methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种新方法来估计在自动驾驶车辆上获得的稀疏激光雷达数据的密集光流。当图像由于例如图像不可靠时，这旨在用作任何基于图像的光流系统的直接替代品。恶劣天气或夜间。为了从离散范围数据中推断出高分辨率2D流，我们设计了一个多块过滤器的三块体系结构，它结合了激光雷达和图像域中的多个中间目标。为了训练这个网络，我们引入了一个包含Kitti数据集大约20K激光雷达样本的数据集，我们使用FlowNet2计算了基于伪地面真实图像的光流。我们展示了我们对Kitti的方法的有效性，并表明尽管使用激光雷达的低分辨率和稀疏测量，我们可以回归密集的光学流动图，这与基于图像的方法估计的相同。

##### URL
[http://arxiv.org/abs/1808.10542](http://arxiv.org/abs/1808.10542)

##### PDF
[http://arxiv.org/pdf/1808.10542](http://arxiv.org/pdf/1808.10542)

