---
layout: post
title: "Face-from-Depth for Head Pose Estimation on Depth Images"
date: 2018-08-30 13:51:43
categories: arXiv_CV
tags: arXiv_CV GAN Face Pose_Estimation CNN Detection
author: Guido Borghi, Matteo Fabbri, Roberto Vezzani, Simone Calderara, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Depth cameras allow to set up reliable solutions for people monitoring and behavior understanding, especially when unstable or poor illumination conditions make unusable common RGB sensors. Therefore, we propose a complete framework for the estimation of the head and shoulder pose based on depth images only. A head detection and localization module is also included, in order to develop a complete end-to-end system. The core element of the framework is a Convolutional Neural Network, called POSEidon+, that receives as input three types of images and provides the 3D angles of the pose as output. Moreover, a Face-from-Depth component based on a Deterministic Conditional GAN model is able to hallucinate a face from the corresponding depth image. We empirically demonstrate that this positively impacts the system performances. We test the proposed framework on two public datasets, namely Biwi Kinect Head Pose and ICT-3DHP, and on Pandora, a new challenging dataset mainly inspired by the automotive setup. Experimental results show that our method overcomes several recent state-of-art works based on both intensity and depth input data, running in real-time at more than 30 frames per second.

##### Abstract (translated by Google)
深度摄像机可以为人们监控和行为理解建立可靠的解决方案，特别是当不稳定或不良照明条件使得无法使用普通RGB传感器时。因此，我们提出了一个完整的框架，用于估计仅基于深度图像的头肩姿势。还包括头部检测和定位模块，以便开发完整的端到端系统。该框架的核心要素是卷积神经网络，称为POSEidon +，它接收三种类型的图像作为输入，并提供姿势的3D角度作为输出。此外，基于确定性条件GAN模型的面部深度分量能够从对应的深度图像幻觉化面部。我们凭经验证明这对系统性能有积极影响。我们在两个公共数据集上测试提议的框架，即Biwi Kinect Head Pose和ICT-3DHP，以及Pandora，这是一个主要受汽车设置启发的新挑战数据集。实验结果表明，我们的方法克服了几种基于强度和深度输入数据的最新工作，以每秒30帧以上的速度实时运行。

##### URL
[http://arxiv.org/abs/1712.05277](http://arxiv.org/abs/1712.05277)

##### PDF
[http://arxiv.org/pdf/1712.05277](http://arxiv.org/pdf/1712.05277)

