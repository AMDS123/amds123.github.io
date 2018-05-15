---
layout: post
title: "LMNet: Real-time Multiclass Object Detection on CPU using 3D LiDARs"
date: 2018-05-13 15:55:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN CNN Quantitative Detection
author: Kazuki Minemura, Hengfui Liau, Abraham Monrroy, Shinpei Kato
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes an optimized single-stage deep convolutional neural network to detect objects in urban environments, using nothing more than point cloud data. This feature enables our method to work regardless the time of the day and the lighting conditions.The proposed network structure employs dilated convolutions to gradually increase the perceptive field as depth increases, this helps to reduce the computation time by about 30\%. The network input consists of five perspective representations of the unorganized point cloud data. The network outputs an objectness map and the bounding box offset values for each point. Our experiments showed that using reflection, range, and the position on each of the three axes helped to improve the location and orientation of the output bounding box. We carried out quantitative evaluations with the help of the KITTI dataset evaluation server. It achieved the fastest processing speed among the other contenders, making it suitable for real-time applications. We implemented and tested it on a real vehicle with a Velodyne HDL-64 mounted on top of it. We achieved execution times as fast as 50 FPS using desktop GPUs, and up to 10 FPS on a single Intel Core i5 CPU. The deploy implementation is open-sourced and it can be found as a feature branch inside the autonomous driving framework Autoware. Code is available at: this https URL

##### Abstract (translated by Google)
本文描述了一种优化的单级深度卷积神经网络，用于检测城市环境中的物体，仅使用点云数据。该特征使我们的方法能够在任何时间和光照条件下工作。所提出的网络结构采用扩张卷积来随着深度增加逐渐增加感知场，这有助于将计算时间减少约30％。网络输入由无组织的点云数据的五个透视表示组成。网络输出一个对象图和每个点的边界框偏移值。我们的实验表明，使用反射，范围和三个轴上每个轴的位置有助于改进输出边界框的位置和方向。我们在KITTI数据集评估服务器的帮助下进行了定量评估。它实现了其他竞争者中最快的处理速度，使其适用于实时应用。我们在其上安装了Velodyne HDL-64的实际车辆上进行实施和测试。我们使用台式机GPU实现了50 FPS的执行时间，单个Intel Core i5 CPU上的执行时间高达10 FPS。部署实施是开源的，可以在自主驾驶框架Autoware中找到它作为功能分支。代码位于：https网址

##### URL
[https://arxiv.org/abs/1805.04902](https://arxiv.org/abs/1805.04902)

##### PDF
[https://arxiv.org/pdf/1805.04902](https://arxiv.org/pdf/1805.04902)

