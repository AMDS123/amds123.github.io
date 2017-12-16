---
layout: post
title: "3DOF Pedestrian Trajectory Prediction Learned from Long-Term Autonomous Mobile Robot Deployment Data"
date: 2017-09-30 00:40:54
categories: arXiv_CV
tags: arXiv_CV Tracking RNN Prediction Detection SLAM
author: Li Sun, Zhi Yan, Sergi Molina Mellado, Marc Hanheide, Tom Duckett
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel 3DOF pedestrian trajectory prediction approach for autonomous mobile service robots. While most previously reported methods are based on learning of 2D positions in monocular camera images, our approach uses range-finder sensors to learn and predict 3DOF pose trajectories (i.e. 2D position plus 1D rotation within the world coordinate system). Our approach, T-Pose-LSTM (Temporal 3DOF-Pose Long-Short-Term Memory), is trained using long-term data from real-world robot deployments and aims to learn context-dependent (environment- and time-specific) human activities. Our approach incorporates long-term temporal information (i.e. date and time) with short-term pose observations as input. A sequence-to-sequence LSTM encoder-decoder is trained, which encodes observations into LSTM and then decodes as predictions. For deployment, it can perform on-the-fly prediction in real-time. Instead of using manually annotated data, we rely on a robust human detection, tracking and SLAM system, providing us with examples in a global coordinate system. We validate the approach using more than 15K pedestrian trajectories recorded in a care home environment over a period of three months. The experiment shows that the proposed T-Pose-LSTM model advances the state-of-the-art 2D-based method for human trajectory prediction in long-term mobile robot deployments.

##### Abstract (translated by Google)
本文提出了一种新的自主移动服务机器人的3DOF行人轨迹预测方法。虽然大多数先前报道的方法是基于在单眼相机图像中的2D位置的学习，但是我们的方法使用测距仪传感器来学习和预测3DOF姿态轨迹（即2D位置加上世界坐标系中的1D旋转）。我们的方法T-Pose-LSTM（时间三维姿态长期短期记忆）是使用来自真实世界机器人部署的长期数据进行训练的，旨在学习依赖于环境和时间的人类活动。我们的方法将长期时间信息（即日期和时间）与短期姿势观察结合起来作为输入。序列到序列的LSTM编码器 - 解码器被训练，将观测值编码成LSTM，然后作为预测进行解码。对于部署，它可以实时执行即时预测。我们依靠强大的人体检测，跟踪和SLAM系统，而不是使用手动注释的数据，为我们提供全球坐标系统中的示例。我们在三个月的时间内使用超过15K的行人轨迹记录在家庭护理环境中来验证这一方法。实验表明，所提出的T-Pose-LSTM模型推进了在长期移动机器人部署中用于人类轨迹预测的最先进的基于2D的方法。

##### URL
[https://arxiv.org/abs/1710.00126](https://arxiv.org/abs/1710.00126)

##### PDF
[https://arxiv.org/pdf/1710.00126](https://arxiv.org/pdf/1710.00126)

