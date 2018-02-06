---
layout: post
title: "Deep Neural Network-based Cooperative Visual Tracking through Multiple Micro Aerial Vehicles"
date: 2018-02-05 10:54:58
categories: arXiv_RO
tags: arXiv_RO Object_Detection Tracking Detection
author: Eric Price, Guilherme Lawless, Heinrich H. B&#xfc;lthoff, Michael Black, Aamir Ahmad
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-camera full-body pose capture of humans and animals in outdoor environments is a highly challenging problem. Our approach to it involves a team of cooperating micro aerial vehicles (MAVs) with on-board cameras only. The key enabling-aspect of our approach is the on-board person detection and tracking method. Recent state-of-the-art methods based on deep neural networks (DNN) are highly promising in this context. However, real time DNNs are severely constrained in input data dimensions, in contrast to available camera resolutions. Therefore, DNNs often fail at objects with small scale or far away from the camera, which are typical characteristics of a scenario with aerial robots. Thus, the core problem addressed in this paper is how to achieve on-board, real-time, continuous and accurate vision-based detections using DNNs for visual person tracking through MAVs. Our solution leverages cooperation among multiple MAVs. First, each MAV fuses its own detections with those obtained by other MAVs to perform cooperative visual tracking. This allows for predicting future poses of the tracked person, which are used to selectively process only the relevant regions of future images, even at high resolutions. Consequently, using our DNN-based detector we are able to continuously track even distant humans with high accuracy and speed. We demonstrate the efficiency of our approach through real robot experiments involving two aerial robots tracking a person, while maintaining an active perception-driven formation. Our solution runs fully on-board our MAV's CPU and GPU, with no remote processing. ROS-based source code is provided for the benefit of the community.

##### Abstract (translated by Google)
多相机全身姿势捕捉室外环境中的人类和动物是非常具有挑战性的问题。我们的方法涉及到一个只有车载摄像头的合作微型飞行器（MAV）团队。我们的方法的关键使能方面是车载人员检测和跟踪方法。基于深度神经网络（DNN）的最新的最先进的方法在这种情况下是非常有前途的。然而，与可用的摄像机分辨率相比，实时DNN在输入数据维度上受到严重限制。因此，DNN往往在小规模物体或远离摄像机的地方出现故障，这是空中机器人场景的典型特征。因此，本文所讨论的核心问题是如何利用DNN实现车载，实时，连续和准确的基于视觉的检测，以便通过MAV进行视觉人员跟踪。我们的解决方案利用多个MAV之间的合作。首先，每个MAV将自己的检测与其他MAV获得的检测融合在一起，进行协作式视觉跟踪。这允许预测被跟踪的人的未来姿势，即使在高分辨率下，也可以选择性地仅处理未来图像的相关区域。因此，使用我们的基于DNN的探测器，我们能够以高精度和高速度持续追踪遥远的人类。我们通过真实的机器人实验来展示我们的方法的效率，其中涉及两个空中机器人跟踪一个人，同时保持积极的感知驱动的形成。我们的解决方案完全在我们的MAV的CPU和GPU上运行，无需远程处理。基于ROS的源代码是为了社区的利益而提供的。

##### URL
[http://arxiv.org/abs/1802.01346](http://arxiv.org/abs/1802.01346)

##### PDF
[http://arxiv.org/pdf/1802.01346](http://arxiv.org/pdf/1802.01346)

