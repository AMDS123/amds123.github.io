---
layout: post
title: "Stereo 3D Object Trajectory Reconstruction"
date: 2018-08-27 15:04:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Sebastian Bullinger, Christoph Bodensteiner, Michael Arens, Rainer Stiefelhagen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to reconstruct the three-dimensional trajectory of a moving instance of a known object category using stereo video data. We track the two-dimensional shape of objects on pixel level exploiting instance-aware semantic segmentation techniques and optical flow cues. We apply Structure from Motion (SfM) techniques to object and background images to determine for each frame initial camera poses relative to object instances and background structures. We refine the initial SfM results by integrating stereo camera constraints exploiting factor graphs. We compute the object trajectory by combining object and background camera pose information. In contrast to stereo matching methods, our approach leverages temporal adjacent views for object point triangulation. As opposed to monocular trajectory reconstruction approaches, our method shows no degenerated cases. We evaluate our approach using publicly available video data of vehicles in urban scenes.

##### Abstract (translated by Google)
我们提出了一种使用立体视频数据重建已知对象类别的移动实例的三维轨迹的方法。我们利用实例感知语义分割技术和光流提示在像素级跟踪对象的二维形状。我们将结构从运动（SfM）技术应用于对象和背景图像，以确定每个帧相对于对象实例和背景结构的初始相机姿势。我们通过利用因子图集成立体相机约束来优化初始SfM结果。我们通过组合对象和背景相机姿势信息来计算对象轨迹。与立体匹配方法相比，我们的方法利用时间相邻视图进行对象点三角测量。与单眼轨迹重建方法相反，我们的方法显示没有退化的情况。我们使用公共可用的城市场景中的车辆视频数据来评估我们的方法。

##### URL
[http://arxiv.org/abs/1808.09297](http://arxiv.org/abs/1808.09297)

##### PDF
[http://arxiv.org/pdf/1808.09297](http://arxiv.org/pdf/1808.09297)

