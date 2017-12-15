---
layout: post
title: "Face-from-Depth for Head Pose Estimation on Depth Images"
date: 2017-12-12 20:57:15
categories: arXiv_CV
tags: arXiv_CV GAN Face Pose_Estimation CNN Detection
author: Guido Borghi, Matteo Fabbri, Roberto Vezzani, Simone Calderara, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Depth cameras allow to setup reliable solutions for people monitoring and behavior understanding, specially when unstable or poor illumination conditions make unusable common RGB sensors. Therefore, we propose a complete framework for the estimation of the head and shoulder pose based on depth images only. A head detection and localization module is also included, in order to develop a complete end-to-end system. The core element of the framework is a Convolutional Neural Network, called POSEidon+, that receives as input three types of images and provides the 3D angles of the pose as output. Moreover, a Face-from-Depth component based on a Deterministic Conditional GAN model is able to hallucinate a face from the corresponding depth image and we empirically demonstrate that this positively impacts the system performances. We test the proposed framework on two public datasets, namely Biwi Kinect Head Pose and ICT-3DHP, and on Pandora, a new challenging dataset mainly inspired by the automotive setup. Experimental results show that our method overcomes all recent state-of-art works based on both intensity and depth input data, running in real time at more than 30 frames per second.

##### Abstract (translated by Google)
深度摄像机可以为人们的监控和行为理解设置可靠的解决方案，特别是在不稳定或较差的照明条件下，不能使用普通的RGB传感器。因此，本文提出了一个完整的基于深度图像的头肩姿势估计框架。还包括头部检测和定位模块，以开发完整的端到端系统。该框架的核心元素是一个名为POSEidon +的卷积神经网络，它接收三种类型的图像并提供姿态的三维角度作为输出。此外，基于确定性条件GAN模型的面部深度分量能够从相应的深度图像幻觉人脸，并且我们凭经验证明这对系统性能有正面影响。我们测试了两个公共数据集（即Biwi Kinect Head Pose和ICT-3DHP）以及Pandora这个新的具有挑战性的数据集的建议框架，这个数据集主要受汽车设置的启发。实验结果表明，我们的方法克服了所有最新的基于强度和深度输入数据的艺术作品，实时运行速度超过每秒30帧。

##### URL
[http://arxiv.org/abs/1712.05277](http://arxiv.org/abs/1712.05277)

##### PDF
[http://arxiv.org/pdf/1712.05277](http://arxiv.org/pdf/1712.05277)

