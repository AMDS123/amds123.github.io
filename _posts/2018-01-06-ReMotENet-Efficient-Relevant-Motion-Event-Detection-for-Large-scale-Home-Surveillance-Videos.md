---
layout: post
title: "ReMotENet: Efficient Relevant Motion Event Detection for Large-scale Home Surveillance Videos"
date: 2018-01-06 15:19:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Attention Tracking Deep_Learning Detection
author: Ruichi Yu, Hongcheng Wang, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of detecting relevant motion caused by objects of interest (e.g., person and vehicles) in large scale home surveillance videos. The traditional method usually consists of two separate steps, i.e., detecting moving objects with background subtraction running on the camera, and filtering out nuisance motion events (e.g., trees, cloud, shadow, rain/snow, flag) with deep learning based object detection and tracking running on cloud. The method is extremely slow and therefore not cost effective, and does not fully leverage the spatial-temporal redundancies with a pre-trained off-the-shelf object detector. To dramatically speedup relevant motion event detection and improve its performance, we propose a novel network for relevant motion event detection, ReMotENet, which is a unified, end-to-end data-driven method using spatial-temporal attention-based 3D ConvNets to jointly model the appearance and motion of objects-of-interest in a video. ReMotENet parses an entire video clip in one forward pass of a neural network to achieve significant speedup. Meanwhile, it exploits the properties of home surveillance videos, e.g., relevant motion is sparse both spatially and temporally, and enhances 3D ConvNets with a spatial-temporal attention model and reference-frame subtraction to encourage the network to focus on the relevant moving objects. Experiments demonstrate that our method can achieve comparable or event better performance than the object detection based method but with three to four orders of magnitude speedup (up to 20k times) on GPU devices. Our network is efficient, compact and light-weight. It can detect relevant motion on a 15s surveillance video clip within 4-8 milliseconds on a GPU and a fraction of second (0.17-0.39) on a CPU with a model size of less than 1MB.

##### Abstract (translated by Google)
本文针对在大型家庭监控视频中检测由感兴趣对象（例如，人和车辆）引起的相关运动的问题。传统的方法通常由两个独立的步骤组成，即通过在摄像机上运行背景减法来检测移动物体，并利用基于深度学习的物体检测滤除干扰运动事件（例如，树木，云，阴影，雨/雪，旗）并跟踪在云上运行。该方法非常慢，因此不具有成本效益，并且不能利用预先训练的现成物体检测器来充分利用空间 - 时间冗余。为了大大加快相关运动事件检测的速度并提高其性能，我们提出了一种新的相关运动事件检测网络ReMotENet，它是一个统一的端到端的数据驱动方法，使用基于时空关注的3D ConvNets联合在视频中模拟感兴趣对象的外观和运动。 ReMotENet在一个神经网络的正向传递中解析整个视频剪辑，以实现显着的加速。同时，利用家庭监控视频的属性，例如相关运动在空间和时间上都是稀疏的，并且利用时空关注模型和参考帧相减来增强3D ConvNet，以鼓励网络关注相关移动对象。实验证明，我们的方法可以实现与基于对象检测的方法相比或事件更好的性能，但在GPU设备上具有三到四个数量级的加速（高达20k倍）。我们的网络高效，紧凑，重量轻。它可以在GPU上以4-8毫秒的速度检测15秒监控视频剪辑上的相关动作，并且在模型尺寸小于1MB的CPU上以秒为单位（0.17-0.39）检测相关动作。

##### URL
[http://arxiv.org/abs/1801.02031](http://arxiv.org/abs/1801.02031)

##### PDF
[http://arxiv.org/pdf/1801.02031](http://arxiv.org/pdf/1801.02031)

