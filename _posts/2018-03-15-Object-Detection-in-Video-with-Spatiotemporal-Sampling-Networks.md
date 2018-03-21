---
layout: post
title: "Object Detection in Video with Spatiotemporal Sampling Networks"
date: 2018-03-15 00:23:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Gedas Bertasius, Lorenzo Torresani, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Spatiotemporal Sampling Network (STSN) that uses deformable convolutions across time for object detection in videos. Our STSN performs object detection in a video frame by learning to spatially sample features from the adjacent frames. This naturally renders the approach robust to occlusion or motion blur in individual frames. Our framework does not require additional supervision, as it optimizes sampling locations directly with respect to object detection performance. Our STSN outperforms the state-of-the-art on the ImageNet VID dataset and compared to prior video object detection methods it uses a simpler design, and does not require optical flow data for training. We also show that after training STSN on videos, we can adapt it for object detection in images, by adding and training a single deformable convolutional layer on still-image data. This leads to improvements in accuracy compared to traditional object detection in images.

##### Abstract (translated by Google)
我们提出了一种时空采样网络（STSN），它使用跨时间变形卷积来进行视频中的物体检测。我们的STSN通过学习对相邻帧的特征进行空间采样来在视频帧中执行对象检测。这自然使得该方法对于单个帧中的遮挡或运动模糊是鲁棒的。我们的框架不需要额外的监督，因为它直接针对物体检测性能优化采样位置。我们的STSN性能优于ImageNet VID数据集的最新技术水平，与之前的视频对象检测方法相比，它采用更简单的设计，并且不需要光流数据进行培训。我们还表明，在对视频进行STSN训练之后，我们可以通过在静止图像数据上添加和训练单个可变形的卷积层来适应图像中的对象检测。与传统的图像中的物体检测相比，这可以提高精确度。

##### URL
[https://arxiv.org/abs/1803.05549](https://arxiv.org/abs/1803.05549)

##### PDF
[https://arxiv.org/pdf/1803.05549](https://arxiv.org/pdf/1803.05549)

