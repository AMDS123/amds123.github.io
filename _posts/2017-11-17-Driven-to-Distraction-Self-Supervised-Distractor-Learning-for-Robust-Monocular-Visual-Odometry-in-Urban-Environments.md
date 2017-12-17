---
layout: post
title: "Driven to Distraction: Self-Supervised Distractor Learning for Robust Monocular Visual Odometry in Urban Environments"
date: 2017-11-17 16:54:40
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Dan Barnes, Will Maddern, Geoffrey Pascoe, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
We present a self-supervised approach to ignoring "distractors" in camera images for the purposes of robustly estimating vehicle motion in cluttered urban environments. We leverage offline multi-session mapping approaches to automatically generate a per-pixel ephemerality mask and depth map for each input image, which we use to train a deep convolutional network. At run-time we use the predicted ephemerality and depth as an input to a monocular visual odometry (VO) pipeline, using either sparse features or dense photometric matching. Our approach yields metric-scale VO using only a single camera and can recover the correct egomotion even when 90% of the image is obscured by dynamic, independently moving objects. We evaluate our robust VO methods on more than 400km of driving from the Oxford RobotCar Dataset and demonstrate reduced odometry drift and significantly improved egomotion estimation in the presence of large moving vehicles in urban traffic.

##### Abstract (translated by Google)
我们提出了一种自我监督的方法来忽略照相机图像中的“干扰”，以便在混乱的城市环境中鲁棒地估计车辆运动。我们利用离线多会话映射方法为每个输入图像自动生成每个像素的短暂掩模和深度图，我们用它来训练深度卷积网络。在运行时，我们使用预测的短暂性和深度作为单目视觉测距（VO）管线的输入，使用稀疏特征或稠密光度匹配。我们的方法只使用一台摄像机即可产生公制尺寸的VO，即使90％的图像被动态的，独立移动的物体所遮挡，也可以恢复正确的运动。我们评估了牛津机器人驾驶汽车数据集超过400公里的强大VO方法，并证明减少odometry漂移，并显着改善城市交通中大型行驶车辆的运动估计。

##### URL
[https://arxiv.org/abs/1711.06623](https://arxiv.org/abs/1711.06623)

##### PDF
[https://arxiv.org/pdf/1711.06623](https://arxiv.org/pdf/1711.06623)

