---
layout: post
title: "R$^3$-Net: A Deep Network for Multi-oriented Vehicle Detection in Aerial Images and Videos"
date: 2018-08-16 16:04:27
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Classification Detection
author: Qingpeng Li, Lichao Mou, Qizhi Xu, Yun Zhang, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Vehicle detection is a significant and challenging task in aerial remote sensing applications. Most existing methods detect vehicles with regular rectangle boxes and fail to offer the orientation of vehicles. However, the orientation information is crucial for several practical applications, such as the trajectory and motion estimation of vehicles. In this paper, we propose a novel deep network, called rotatable region-based residual network (R$^3$-Net), to detect multi-oriented vehicles in aerial images and videos. More specially, R$^3$-Net is utilized to generate rotatable rectangular target boxes in a half coordinate system. First, we use a rotatable region proposal network (R-RPN) to generate rotatable region of interests (R-RoIs) from feature maps produced by a deep convolutional neural network. Here, a proposed batch averaging rotatable anchor (BAR anchor) strategy is applied to initialize the shape of vehicle candidates. Next, we propose a rotatable detection network (R-DN) for the final classification and regression of the R-RoIs. In R-DN, a novel rotatable position sensitive pooling (R-PS pooling) is designed to keep the position and orientation information simultaneously while downsampling the feature maps of R-RoIs. In our model, R-RPN and R-DN can be trained jointly. We test our network on two open vehicle detection image datasets, namely DLR 3K Munich Dataset and VEDAI Dataset, demonstrating the high precision and robustness of our method. In addition, further experiments on aerial videos show the good generalization capability of the proposed method and its potential for vehicle tracking in aerial videos. The demo video is available at https://youtu.be/xCYD-tYudN0.

##### Abstract (translated by Google)
车辆检测是航空遥感应用中的重要且具有挑战性的任务。大多数现有方法检测具有常规矩形框的车辆并且不能提供车辆的方向。然而，方向信息对于若干实际应用是至关重要的，例如车辆的轨迹和运动估计。在本文中，我们提出了一种新的深度网络，称为可旋转的基于区域的残留网络（R $ ^ 3 $ -Net），用于检测航空图像和视频中的多向车辆。更具体地说，R $ ^ 3 $ -Net用于在半坐标系中生成可旋转的矩形目标盒。首先，我们使用可旋转区域提议网络（R-RPN）从深度卷积神经网络产生的特征图生成可旋转的兴趣区域（R-RoI）。这里，应用所提出的批量平均可旋转锚（BAR锚）策略来初始化车辆候选者的形状。接下来，我们提出了一个可旋转的检测网络（R-DN），用于R-RoI的最终分类和回归。在R-DN中，设计了一种新颖的可旋转位置敏感池（R-PS池），以同时保持位置和方向信息，同时对R-RoI的特征图进行下采样。在我们的模型中，R-RPN和R-DN可以联合培训。我们在两个开放式车辆检测图像数据集上测试我们的网络，即DLR 3K Munich Dataset和VEDAI Dataset，展示了我们方法的高精度和稳健性。此外，对航拍视频的进一步实验表明，该方法具有良好的泛化能力，并具有航拍视频中车辆跟踪的潜力。演示视频可在https://youtu.be/xCYD-tYudN0上找到。

##### URL
[http://arxiv.org/abs/1808.05560](http://arxiv.org/abs/1808.05560)

##### PDF
[http://arxiv.org/pdf/1808.05560](http://arxiv.org/pdf/1808.05560)

