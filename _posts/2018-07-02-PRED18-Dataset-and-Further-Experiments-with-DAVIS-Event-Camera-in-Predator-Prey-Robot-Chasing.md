---
layout: post
title: "PRED18: Dataset and Further Experiments with DAVIS Event Camera in Predator-Prey Robot Chasing"
date: 2018-07-02 18:07:18
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning
author: Diederik Paul Moeys, Daniel Neil, Federico Corradi, Emmett Kerr, Philip Vance, Gautham Das, Sonya A. Coleman, Thomas M. McGinnity, Dermot Kerr, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Machine vision systems using convolutional neural networks (CNNs) for robotic applications are increasingly being developed. Conventional vision CNNs are driven by camera frames at constant sample rate, thus achieving a fixed latency and power consumption tradeoff. This paper describes further work on the first experiments of a closed-loop robotic system integrating a CNN together with a Dynamic and Active Pixel Vision Sensor (DAVIS) in a predator/prey scenario. The DAVIS, mounted on the predator Summit XL robot, produces frames at a fixed 15 Hz frame-rate and Dynamic Vision Sensor (DVS) histograms containing 5k ON and OFF events at a variable frame-rate ranging from 15-500 Hz depending on the robot speeds. In contrast to conventional frame-based systems, the latency and processing cost depends on the rate of change of the image. The CNN is trained offline on the 1.25h labeled dataset to recognize the position and size of the prey robot, in the field of view of the predator. During inference, combining the ten output classes of the CNN allows extracting the analog position vector of the prey relative to the predator with a mean 8.7% error in angular estimation. The system is compatible with conventional deep learning technology, but achieves a variable latency-power tradeoff that adapts automatically to the dynamics. Finally, investigations on the robustness of the algorithm, a human performance comparison and a deconvolution analysis are also explored.

##### Abstract (translated by Google)
使用卷积神经网络（CNN）用于机器人应用的机器视觉系统正在逐渐发展。传统的视觉CNN由相机帧以恒定的采样率驱动，从而实现固定的延迟和功耗折衷。本文描述了在捕食者/猎物情景中将CNN与动态和有源像素视觉传感器（DAVIS）集成在一起的闭环机器人系统的第一次实验的进一步研究。 DAVIS安装在捕食者Summit XL机器人上，以固定的15 Hz帧速率生成帧，动态视觉传感器（DVS）直方图包含5k ON和OFF事件，可变帧速率范围为15-500 Hz，具体取决于机器人速度。与传统的基于帧的系统相比，延迟和处理成本取决于图像的变化率。 CNN在1.25h标记数据集上离线训练，以识别捕食者视野中猎物机器人的位置和大小。在推理期间，组合CNN的十个输出类别允许相对于捕食者提取猎物的模拟位置矢量，角度估计的平均误差为8.7％。该系统与传统的深度学习技术兼容，但实现了可变延迟 - 功率权衡，可自动适应动态。最后，还研究了算法的鲁棒性，人体性能比较和反卷积分析。

##### URL
[http://arxiv.org/abs/1807.03128](http://arxiv.org/abs/1807.03128)

##### PDF
[http://arxiv.org/pdf/1807.03128](http://arxiv.org/pdf/1807.03128)

