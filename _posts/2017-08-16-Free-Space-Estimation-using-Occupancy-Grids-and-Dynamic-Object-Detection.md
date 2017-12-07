---
layout: post
title: "Free Space Estimation using Occupancy Grids and Dynamic Object Detection"
date: 2017-08-16 17:28:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Detection
author: Raghavender Sahdev
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an approach to estimate Free Space from a Stereo image pair using stochastic occupancy grids. We do this in the domain of autonomous driving on the famous benchmark dataset KITTI. Later based on the generated occupancy grid we match 2 image sequences to compute the top view representation of the map. We do this to map the environment. We compute a transformation between the occupancy grids of two successive images and use it to compute the top view map. Two issues need to be addressed for mapping are discussed - computing a map and dealing with dynamic objects for computing the map. Dynamic Objects are detected in successive images based on an idea similar to tracking of foreground objects from the background objects based on motion flow. A novel RANSAC based segmentation approach has been proposed here to address this issue.

##### Abstract (translated by Google)
在本文中，我们提出了一个方法来估计自由空间从立体图像对使用随机占用网格。我们在着名的基准数据集KITTI的自主驾驶领域做到这一点。稍后基于生成的占用网格，我们匹配2个图像序列来计算地图的顶视图表示。我们这样做来映射环境。我们计算两个连续图像的占用网格之间的转换，并使用它来计算顶视图图。讨论映射的两个问题需要讨论 - 计算地图并处理用于计算地图的动态对象。基于类似于基于运动流从背景对象跟踪前景对象的想法在连续图像中检测动态对象。这里提出了一种新的基于RANSAC的分割方法来解决这个问题。

##### URL
[https://arxiv.org/abs/1708.04989](https://arxiv.org/abs/1708.04989)

##### PDF
[https://arxiv.org/pdf/1708.04989](https://arxiv.org/pdf/1708.04989)

