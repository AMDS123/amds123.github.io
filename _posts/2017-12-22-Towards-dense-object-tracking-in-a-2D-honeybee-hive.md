---
layout: post
title: "Towards dense object tracking in a 2D honeybee hive"
date: 2017-12-22 07:20:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Tracking CNN Object_Tracking Detection
author: Katarzyna Bozek, Laetitia Hebert, Alexander S Mikheyev, Greg J Stephens
mathjax: true
---

* content
{:toc}

##### Abstract
From human crowds to cells in tissue, the detection and efficient tracking of multiple objects in dense configurations is an important and unsolved problem. In the past, limitations of image analysis have restricted studies of dense groups to tracking a single or subset of marked individuals, or to coarse-grained group-level dynamics, all of which yield incomplete information. Here, we combine convolutional neural networks (CNNs) with the model environment of a honeybee hive to automatically recognize all individuals in a dense group from raw image data. We create new, adapted individual labeling and use the segmentation architecture U-Net with a loss function dependent on both object identity and orientation. We additionally exploit temporal regularities of the video recording in a recurrent manner and achieve near human-level performance while reducing the network size by 94% compared to the original U-Net architecture. Given our novel application of CNNs, we generate extensive problem-specific image data in which labeled examples are produced through a custom interface with Amazon Mechanical Turk. This dataset contains over 375,000 labeled bee instances across 720 video frames at 2 FPS, representing an extensive resource for the development and testing of tracking methods. We correctly detect 96% of individuals with a location error of ~7% of a typical body dimension, and orientation error of 12 degrees, approximating the variability of human raters. Our results provide an important step towards efficient image-based dense object tracking by allowing for the accurate determination of object location and orientation across time-series image data efficiently within one network architecture.

##### Abstract (translated by Google)
从人群到组织中的细胞，密集配置中多个物体的检测和有效跟踪是一个重要而未解决的问题。过去，图像分析的局限性限制了密集群体的研究，以追踪标记个体的单个或子集，或限制粗粒度的群体级动态，所有这些都会产生不完整的信息。在这里，我们将卷积神经网络（CNN）与蜜蜂蜂房的模型环境相结合，从原始图像数据中自动识别密集组中的所有个体。我们创建新的，适应的个体标签，并使用具有依赖于对象身份和方向的损失函数的分割体系结构U-Net。我们另外利用视频录制的时间规律，实现接近人类的性能，同时比原来的U-Net架构减少了94％的网络尺寸。鉴于我们的CNN新颖的应用程序，我们生成广泛的问题特定的图像数据，其中标记的例子是通过与亚马逊Mechanical Turk的自定义接口产生的。该数据集包含超过375,000个标记的蜜蜂实例，以2 FPS的720个视频帧为代表，为开发和测试追踪方法提供了广泛的资源。我们正确地检测出96％的个体具有典型体尺寸的约7％的位置误差，并且方位误差为12度，近似于人类评价者的变化性。我们的结果为高效的基于图像的密集对象跟踪提供了重要的一步，允许在一个网络体系结构内有效地确定跨时间序列图像数据的对象位置和方向。

##### URL
[https://arxiv.org/abs/1712.08324](https://arxiv.org/abs/1712.08324)

##### PDF
[https://arxiv.org/pdf/1712.08324](https://arxiv.org/pdf/1712.08324)

