---
layout: post
title: "Spatial Pyramid Context-Aware Moving Object Detection and Tracking for Full Motion Video and Wide Aerial Motion Imagery"
date: 2017-11-05 20:07:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Mahdieh Poostchi
mathjax: true
---

* content
{:toc}

##### Abstract
A robust and fast automatic moving object detection and tracking system is essential to characterize target object and extract spatial and temporal information for different functionalities including video surveillance systems, urban traffic monitoring and navigation, robotic. In this dissertation, I present a collaborative Spatial Pyramid Context-aware moving object detection and Tracking system. The proposed visual tracker is composed of one master tracker that usually relies on visual object features and two auxiliary trackers based on object temporal motion information that will be called dynamically to assist master tracker. SPCT utilizes image spatial context at different level to make the video tracking system resistant to occlusion, background noise and improve target localization accuracy and robustness. We chose a pre-selected seven-channel complementary features including RGB color, intensity and spatial pyramid of HoG to encode object color, shape and spatial layout information. We exploit integral histogram as building block to meet the demands of real-time performance. A novel fast algorithm is presented to accurately evaluate spatially weighted local histograms in constant time complexity using an extension of the integral histogram method. Different techniques are explored to efficiently compute integral histogram on GPU architecture and applied for fast spatio-temporal median computations and 3D face reconstruction texturing. We proposed a multi-component framework based on semantic fusion of motion information with projected building footprint map to significantly reduce the false alarm rate in urban scenes with many tall structures. The experiments on extensive VOTC2016 benchmark dataset and aerial video confirm that combining complementary tracking cues in an intelligent fusion framework enables persistent tracking for Full Motion Video and Wide Aerial Motion Imagery.

##### Abstract (translated by Google)
一个强大而快速的自动运动目标检测和跟踪系统对于表征目标对象和提取不同功能（包括视频监控系统，城市交通监控和导航，机器人等）的时空信息至关重要。在本论文中，我提出了一个协作的空间金字塔上下文感知移动对象检测和跟踪系统。所提出的视觉追踪器由一个通常依赖于视觉对象特征的主跟踪器和基于对象时间运动信息的两个辅助跟踪器组成，所述对象时间运动信息将被动态地调用以协助主跟踪器。 SPCT利用不同层次的图像空间上下文，使视频跟踪系统抵抗遮挡，背景噪声，提高目标定位精度和鲁棒性。我们选择了一个预先选定的七通道互补功能，包括HoG的RGB颜色，亮度和空间金字塔，对物体的颜色，形状和空间布局信息进行编码。我们利用积分直方图作为构建块来满足实时性能的需求。提出了一种新的快速算法，用积分直方图方法的扩展来精确评估恒定时间复杂度下的空间加权局部直方图。探索不同的技术来有效地计算GPU架构上的积分直方图，并应用于快速时空中值计算和三维人脸重建纹理化。我们提出了一种基于运动信息语义融合的多组件框架与预测的建筑物足迹地图，大大降低了高架结构的城市场景的虚警率。在广泛的VOTC2016基准数据集和航拍视频上进行的实验证实，在智能融合框架中结合补充跟踪线索可以实现全动态视频和宽空间运动影像的持续跟踪。

##### URL
[https://arxiv.org/abs/1711.01656](https://arxiv.org/abs/1711.01656)

##### PDF
[https://arxiv.org/pdf/1711.01656](https://arxiv.org/pdf/1711.01656)

