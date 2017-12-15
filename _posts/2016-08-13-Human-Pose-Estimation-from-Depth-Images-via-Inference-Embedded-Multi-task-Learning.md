---
layout: post
title: "Human Pose Estimation from Depth Images via Inference Embedded Multi-task Learning"
date: 2016-08-13 03:16:47
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference Prediction
author: Keze Wang, Shengfu Zhai, Hui Cheng, Xiaodan Liang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose estimation (i.e., locating the body parts / joints of a person) is a fundamental problem in human-computer interaction and multimedia applications. Significant progress has been made based on the development of depth sensors, i.e., accessible human pose prediction from still depth images [32]. However, most of the existing approaches to this problem involve several components/models that are independently designed and optimized, leading to suboptimal performances. In this paper, we propose a novel inference-embedded multi-task learning framework for predicting human pose from still depth images, which is implemented with a deep architecture of neural networks. Specifically, we handle two cascaded tasks: i) generating the heat (confidence) maps of body parts via a fully convolutional network (FCN); ii) seeking the optimal configuration of body parts based on the detected body part proposals via an inference built-in MatchNet [10], which measures the appearance and geometric kinematic compatibility of body parts and embodies the dynamic programming inference as an extra network layer. These two tasks are jointly optimized. Our extensive experiments show that the proposed deep model significantly improves the accuracy of human pose estimation over other several state-of-the-art methods or SDKs. We also release a large-scale dataset for comparison, which includes 100K depth images under challenging scenarios.

##### Abstract (translated by Google)
人的姿势估计（即定位人的身体部位/关节）是人机交互和多媒体应用中的基本问题。基于深度传感器的发展已经取得了重大进展，即从静止深度图像可访问的人体姿态预测[32]。然而，这个问题的大多数现有方法涉及若干个独立设计和优化的组件/模型，导致次优性能。在本文中，我们提出了一个新的推理嵌入式多任务学习框架，从静止深度图像预测人体姿态，这是一个神经网络的深层结构实施。具体而言，我们处理两个级联任务：i）通过完全卷积网络（FCN）生成身体部位的热量（置信度）图; ii）通过内置的MatchNet [10]推理机制，根据检测到的身体部位建议寻求身体部位的最佳配置，该系统测量身体部位的外观和几何运动兼容性，并作为额外的网络层体现动态编程推理。这两项任务是共同优化的。我们广泛的实验表明，所提出的深度模型显着提高了人类姿态估计的精度，而不是其他几种最先进的方法或SDK。我们还发布了一个用于比较的大型数据集，其中包括在具有挑战性的场景下的100K深度图像。

##### URL
[https://arxiv.org/abs/1608.03932](https://arxiv.org/abs/1608.03932)

##### PDF
[https://arxiv.org/pdf/1608.03932](https://arxiv.org/pdf/1608.03932)

