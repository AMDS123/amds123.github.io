---
layout: post
title: "Autonomous Quadrotor Landing using Deep Reinforcement Learning"
date: 2018-02-27 10:14:24
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Riccardo Polvara, Massimiliano Patacchiola, Sanjay Sharma, Jian Wan, Andrew Manning, Robert Sutton, Angelo Cangelosi
mathjax: true
---

* content
{:toc}

##### Abstract
Landing an unmanned aerial vehicle (UAV) on a ground marker is an open problem despite the effort of the research community. Previous attempts mostly focused on the analysis of hand-crafted geometric features and the use of external sensors in order to allow the vehicle to approach the land-pad. In this article, we propose a method based on deep reinforcement learning that only requires low-resolution images taken from a down-looking camera in order to identify the position of the marker and land the UAV on it. The proposed approach is based on a hierarchy of Deep Q-Networks (DQNs) used as high-level control policy for the navigation toward the marker. We implemented different technical solutions, such as the combination of vanilla and double DQNs, and a partitioned buffer replay. Using domain randomization we trained the vehicle on uniform textures and we tested it on a large variety of simulated and real-world environments. The overall performance is comparable with a state-of-the-art algorithm and human pilots.

##### Abstract (translated by Google)
尽管研究界努力，将无人驾驶飞行器（UAV）着陆在地面标记上仍是一个悬而未决的问题。以前的尝试主要集中在手工制作几何特征的分析以及使用外部传感器以使车辆接近焊盘。在本文中，我们提出了一种基于深度强化学习的方法，该方法仅需要从俯视相机拍摄的低分辨率图像，以确定标记的位置并将无人机放在其上。所提出的方法基于深Q网络（DQN）的层次结构，用作向标记导航的高级控制策略。我们实施了不同的技术解决方案，例如香草和双DQN的组合以及分区缓冲重放。使用领域随机化，我们对车辆进行了统一纹理训练，并在各种模拟和现实环境中对其进行了测试。整体性能与最先进的算法和人类飞行员相媲美。

##### URL
[http://arxiv.org/abs/1709.03339](http://arxiv.org/abs/1709.03339)

##### PDF
[http://arxiv.org/pdf/1709.03339](http://arxiv.org/pdf/1709.03339)

