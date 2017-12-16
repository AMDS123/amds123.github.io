---
layout: post
title: "Understanding Traffic Density from Large-Scale Web Camera Data"
date: 2017-06-30 20:10:48
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Deep_Learning Prediction Detection
author: Shanghang Zhang, Guanhang Wu, João P. Costeira, José M. F. Moura
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding traffic density from large-scale web camera (webcam) videos is a challenging problem because such videos have low spatial and temporal resolution, high occlusion and large perspective. To deeply understand traffic density, we explore both deep learning based and optimization based methods. To avoid individual vehicle detection and tracking, both methods map the image into vehicle density map, one based on rank constrained regression and the other one based on fully convolution networks (FCN). The regression based method learns different weights for different blocks in the image to increase freedom degrees of weights and embed perspective information. The FCN based method jointly estimates vehicle density map and vehicle count with a residual learning framework to perform end-to-end dense prediction, allowing arbitrary image resolution, and adapting to different vehicle scales and perspectives. We analyze and compare both methods, and get insights from optimization based method to improve deep model. Since existing datasets do not cover all the challenges in our work, we collected and labelled a large-scale traffic video dataset, containing 60 million frames from 212 webcams. Both methods are extensively evaluated and compared on different counting tasks and datasets. FCN based method significantly reduces the mean absolute error from 10.99 to 5.31 on the public dataset TRANCOS compared with the state-of-the-art baseline.

##### Abstract (translated by Google)
从大型网络摄像机（摄像头）视频中了解流量密度是一个具有挑战性的问题，因为这些视频的空间和时间分辨率低，遮挡力高，视角大。为了深入了解交通密度，我们探索了基于深度学习和基于优化的方法。为了避免个体车辆检测和跟踪，这两种方法将图像映射到车辆密度图，一个基于秩约束回归，另一个基于完全卷积网络（FCN）。基于回归的方法学习图像中不同块的不同权重以增加权重的自由度并嵌入透视信息。基于FCN的方法利用残差学习框架联合估计车辆密度图和车辆数量，以执行端到端密集预测，允许任意图像分辨率，并适应不同的车辆尺度和视角。我们分析和比较这两种方法，并从基于优化的方法中获得见解来改进深度模型。由于现有的数据集不能覆盖我们工作中的所有挑战，因此我们收集并贴上了一个大型交通视频数据集，其中包含212个网络摄像机的6000万帧。两种方法在不同的计数任务和数据集上进行了广泛的评估和比较。基于FCN的方法将公共数据集TRANCOS中的平均绝对误差从10.99降低到5.31，与最先进的基线相比显着降低。

##### URL
[https://arxiv.org/abs/1703.05868](https://arxiv.org/abs/1703.05868)

##### PDF
[https://arxiv.org/pdf/1703.05868](https://arxiv.org/pdf/1703.05868)

