---
layout: post
title: "Active Image-based Modeling"
date: 2017-05-02 15:06:36
categories: arXiv_CV
tags: arXiv_CV
author: Rui Huang (1), Danping Zou (2), Richard Vaughan (1), Ping Tan (1) ((1) Simon Fraser University, (2) Shanghai Jiao Tong University)
mathjax: true
---

* content
{:toc}

##### Abstract
We seek to automate the data capturing process in image-based modeling, which is often tedious and time consuming now. At the heart of our system is an iterative linear method to solve the multi-view stereo (MVS) problem quickly. Unlike conventional MVS algorithms that solve a per-pixel depth at each input image, we represent the depth map at each image as a piecewise planar triangle mesh and solve it by an iterative linear method. The edges of the triangle mesh are snapped to image edges to better capture scene structures. Our fast MVS algorithm enables online model reconstruction and quality assessment to determine the next-best-views (NBVs) for modeling. The NBVs are searched in a plane above unreconstructed shapes. In this way, our path planning can use the result from 3D reconstruction to guarantee obstacle avoidance. We test this system with an unmanned aerial vehicle (UAV) in a simulator, an indoor motion capture system (Vicon) room, and outdoor open spaces.

##### Abstract (translated by Google)
我们试图在基于图像的建模中实现数据采集过程的自动化，而这往往是乏味和耗时的。我们系统的核心是快速解决多视点立体（MVS）问题的迭代线性方法。与传统的MVS算法不同，在每个输入图像上求解每像素深度，我们将每个图像的深度图表示为分段平面三角网格，并通过迭代线性方法求解。三角形网格的边缘与图像边缘对齐以更好地捕捉场景结构。我们的快速MVS算法能够进行在线模型重建和质量评估，以确定建模的次最佳视图（NBV）。 NBV在未构造形状上方的平面中搜索。这样，我们的路径规划就可以利用三维重建的结果来保证避障。我们在模拟器，室内动作捕捉系统（Vicon）房间和户外开放空间中使用无人驾驶飞行器（UAV）测试该系统。

##### URL
[https://arxiv.org/abs/1705.01010](https://arxiv.org/abs/1705.01010)

##### PDF
[https://arxiv.org/pdf/1705.01010](https://arxiv.org/pdf/1705.01010)

