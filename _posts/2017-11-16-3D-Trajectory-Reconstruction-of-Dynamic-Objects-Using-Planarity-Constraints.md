---
layout: post
title: "3D Trajectory Reconstruction of Dynamic Objects Using Planarity Constraints"
date: 2017-11-16 15:21:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Drone Semantic_Segmentation Quantitative
author: Sebastian Bullinger, Christoph Bodensteiner, Michael Arens, Rainer Stiefelhagen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to reconstruct the three-dimensional trajectory of a moving instance of a known object category in monocular video data. We track the two-dimensional shape of objects on pixel level exploiting instance-aware semantic segmentation techniques and optical flow cues. We apply Structure from Motion techniques to object and background images to determine for each frame camera poses relative to object instances and background structures. By combining object and background camera pose information, we restrict the object trajectory to a one-parameter family of possible solutions. We compute a ground representation by fusing background structures and corresponding semantic segmentations. This allows us to determine an object trajectory consistent to image observations and reconstructed environment model. Our method is robust to occlusion and handles temporarily stationary objects. We show qualitative results using drone imagery. Due to the lack of suitable benchmark datasets we present a new dataset to evaluate the quality of reconstructed three-dimensional object trajectories. The video sequences contain vehicles in urban areas and are rendered using the path-tracing render engine Cycles to achieve realistic results. We perform a quantitative evaluation of the presented approach using this dataset. Our algorithm achieves an average reconstruction-to-ground-truth distance of 0.31 meter.

##### Abstract (translated by Google)
我们提出了一种在单目视频数据中重建已知对象类别的移动实例的三维轨迹的方法。我们利用实例感知的语义分割技术和光流量线索来跟踪像素级上的物体的二维形状。我们将结构从运动技术应用到对象和背景图像，以确定每个帧相机的姿势相对于对象实例和背景结构。通过结合物体和背景摄像机姿态信息，我们将物体轨迹限制为一个可能的解决方案的单参数族。我们通过融合背景结构和相应的语义分割来计算地面表示。这使我们能够确定一个与图像观测和重建环境模型一致的物体轨迹。我们的方法是强大的闭塞和暂时处理静止的对象。我们使用无人机图像显示定性结果。由于缺乏合适的基准数据集，我们提出了一个新的数据集来评估重建的三维物体轨迹的质量。视频序列包含城市地区的车辆，并使用路径追踪渲染引擎循环渲染，以获得逼真的效果。我们使用这个数据集对提出的方法进行定量评估。我们的算法实现了0.31米的平均重建距离真实距离。

##### URL
[https://arxiv.org/abs/1711.06136](https://arxiv.org/abs/1711.06136)

##### PDF
[https://arxiv.org/pdf/1711.06136](https://arxiv.org/pdf/1711.06136)

