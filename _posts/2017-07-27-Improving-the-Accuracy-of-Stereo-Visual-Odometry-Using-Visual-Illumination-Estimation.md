---
layout: post
title: "Improving the Accuracy of Stereo Visual Odometry Using Visual Illumination Estimation"
date: 2017-07-27 22:27:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lee Clement, Valentin Peretroukhin, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
In the absence of reliable and accurate GPS, visual odometry (VO) has emerged as an effective means of estimating the egomotion of robotic vehicles. Like any dead-reckoning technique, VO suffers from unbounded accumulation of drift error over time, but this accumulation can be limited by incorporating absolute orientation information from, for example, a sun sensor. In this paper, we leverage recent work on visual outdoor illumination estimation to show that estimation error in a stereo VO pipeline can be reduced by inferring the sun position from the same image stream used to compute VO, thereby gaining the benefits of sun sensing without requiring a dedicated sun sensor or the sun to be visible to the camera. We compare sun estimation methods based on hand-crafted visual cues and Convolutional Neural Networks (CNNs) and demonstrate our approach on a combined 7.8 km of urban driving from the popular KITTI dataset, achieving up to a 43% reduction in translational average root mean squared error (ARMSE) and a 59% reduction in final translational drift error compared to pure VO alone.

##### Abstract (translated by Google)
在没有可靠和精确的GPS的情况下，视觉测距（VO）已经成为评估机器人车辆运动的有效手段。像任何航位推测技术一样，VO受到随时间漂移误差的无限累积的影响，但是这种积累可以通过结合来自例如太阳传感器的绝对定向信息来限制。在本文中，我们利用最近在视觉户外照明估计方面的工作，以显示通过从用于计算VO的相同图像流中推断太阳位置，可以减少立体声VO管线中的估计误差，从而获得太阳感测的益处而不需要一个专用的太阳感应器或太阳照相机可见。我们比较了基于手工制作的视觉线索和卷积神经网络（CNN）的太阳估计方法，并且从流行的KITTI数据集结合7.8公里城市驾驶演示了我们的方法，平均均方根平方减少了43％误差（ARMSE）和最终的平移漂移误差减少了59％。

##### URL
[https://arxiv.org/abs/1609.04705](https://arxiv.org/abs/1609.04705)

##### PDF
[https://arxiv.org/pdf/1609.04705](https://arxiv.org/pdf/1609.04705)

