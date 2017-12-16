---
layout: post
title: "Real-time Human Pose Estimation from Video with Convolutional Neural Networks"
date: 2016-09-23 16:22:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Tracking Action_Recognition CNN Detection Recognition
author: Marko Linna, Juho Kannala, Esa Rahtu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method for real-time multi-person human pose estimation from video by utilizing convolutional neural networks. Our method is aimed for use case specific applications, where good accuracy is essential and variation of the background and poses is limited. This enables us to use a generic network architecture, which is both accurate and fast. We divide the problem into two phases: (1) pre-training and (2) finetuning. In pre-training, the network is learned with highly diverse input data from publicly available datasets, while in finetuning we train with application specific data, which we record with Kinect. Our method differs from most of the state-of-the-art methods in that we consider the whole system, including person detector, pose estimator and an automatic way to record application specific training material for finetuning. Our method is considerably faster than many of the state-of-the-art methods. Our method can be thought of as a replacement for Kinect, and it can be used for higher level tasks, such as gesture control, games, person tracking, action recognition and action tracking. We achieved accuracy of 96.8\% (PCK@0.2) with application specific data.

##### Abstract (translated by Google)
在本文中，我们提出了一种利用卷积神经网络从视频进行实时多人人体姿态估计的方法。我们的方法是针对用例的具体应用，其中良好的准确性是必不可少的，背景和姿势的变化是有限的。这使我们能够使用通用的网络架构，既精确又快速。我们将问题分为两个阶段：（1）预训练和（2）微调。在预训练中，网络学习来自公开数据集的高度多样化的输入数据，而在微调中，我们使用Kinect记录的应用程序特定数据进行训练。我们的方法不同于大多数最先进的方法，因为我们考虑整个系统，包括人员检测器，姿态估计器和自动方式来记录应用程序特定的训练材料的微调。我们的方法比许多最先进的方法要快得多。我们的方法可以被认为是Kinect的替代品，可以用于更高层次的任务，如手势控制，游戏，人物追踪，动作识别和动作追踪。我们用专用数据达到了96.8％的准确度（PCK@0.2）。

##### URL
[https://arxiv.org/abs/1609.07420](https://arxiv.org/abs/1609.07420)

##### PDF
[https://arxiv.org/pdf/1609.07420](https://arxiv.org/pdf/1609.07420)

