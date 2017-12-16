---
layout: post
title: "Robust Multi-view Pedestrian Tracking Using Neural Networks"
date: 2017-04-21 00:12:23
categories: arXiv_CV
tags: arXiv_CV Tracking Classification Detection
author: Md Zahangir Alom, Tarek M. Taha
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a real-time robust multi-view pedestrian detection and tracking system for video surveillance using neural networks which can be used in dynamic environments. The proposed system consists of two phases: multi-view pedestrian detection and tracking. First, pedestrian detection utilizes background subtraction to segment the foreground blob. An adaptive background subtraction method where each of the pixel of input image models as a mixture of Gaussians and uses an on-line approximation to update the model applies to extract the foreground region. The Gaussian distributions are then evaluated to determine which are most likely to result from a background process. This method produces a steady, real-time tracker in outdoor environment that consistently deals with changes of lighting condition, and long-term scene change. Second, the Tracking is performed at two phases: pedestrian classification and tracking the individual subject. A sliding window is applied on foreground binary image to select an input window which is used for selecting the input image patches from actually input frame. The neural networks is used for classification with PHOG features. Finally, a Kalman filter is applied to calculate the subsequent step for tracking that aims at finding the exact position of pedestrians in an input image. The experimental result shows that the proposed approach yields promising performance on multi-view pedestrian detection and tracking on different benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一个实时鲁棒的多视图行人检测和跟踪系统的视频监控使用神经网络，可用于动态环境。所提出的系统由两个阶段组成：多视图行人检测和跟踪。首先，行人检测利用背景减法来分割前景斑点。一种自适应背景减法方法，其中输入图像的每个像素作为高斯混合，并使用在线近似来更新模型适用于提取前景区域。然后评估高斯分布以确定最有可能由后台处理产生哪些分布。这种方法在室外环境中产生一个稳定的，实时的跟踪器，一贯处理照明条件的变化和长期的场景变化。其次，追踪分两个阶段进行：行人分类和追踪个人主题。在前景二值图像上应用滑动窗口来选择用于从实际输入帧中选择输入图像块的输入窗口。神经网络用于PHOG特征的分类。最后，应用卡尔曼滤波器来计算用于追踪的后续步骤，其目的在于找到输入图像中行人的精确位置。实验结果表明，所提出的方法在不同的基准数据集上进行多视图行人检测和跟踪时具有良好的性能。

##### URL
[https://arxiv.org/abs/1704.06370](https://arxiv.org/abs/1704.06370)

##### PDF
[https://arxiv.org/pdf/1704.06370](https://arxiv.org/pdf/1704.06370)

