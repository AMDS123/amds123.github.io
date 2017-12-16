---
layout: post
title: "Fine-Grained Head Pose Estimation Without Keypoints"
date: 2017-12-01 17:25:56
categories: arXiv_CV
tags: arXiv_CV Attention GAN Face Pose_Estimation CNN Classification Detection
author: Nataniel Ruiz, Eunji Chong, James M. Rehg
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the head pose of a person is a crucial problem that has a large amount of applications such as aiding in gaze estimation, modeling attention, fitting 3D models to video and performing face alignment. Traditionally head pose is computed by estimating some keypoints from the target face and solving the 2D to 3D correspondence problem with a mean human head model. We argue that this is a fragile method because it relies entirely on landmark detection performance, the extraneous head model and an ad-hoc fitting step. We present an elegant and robust way to determine pose by training a multi-loss convolutional neural network on 300W-LP, a large synthetically expanded dataset, to predict intrinsic Euler angles (yaw, pitch and roll) directly from image intensities through joint binned pose classification and regression. We present empirical tests on common in-the-wild pose benchmark datasets which show state-of-the-art results. Additionally we test our method on a dataset usually used for pose estimation using depth and start to close the gap with state-of-the-art depth pose methods. We open-source our training and testing code as well as release our pre-trained models which can be found at this https URL

##### Abstract (translated by Google)
估计人的头部姿态是具有大量应用的关键问题，诸如帮助注视估计，建模注意力，将3D模型拟合到视频以及执行面部对准。传统的头部姿势是通过估计来自目标人脸的一些关键点并利用平均人类头部模型解决二维到三维对应问题来计算的。我们认为这是一个脆弱的方法，因为它完全依赖于标志性检测性能，无关的头部模型和专门的拟合步骤。我们提出了一个优雅和稳健的方式来确定姿态，通过训练300W-LP（一个大型的综合扩展数据集）上的多损失卷积神经网络，通过联合装仓姿势直接从图像强度预测内在欧拉角（偏航，俯仰和滚转）分类和回归。我们提供了显示最新结果的常见野外姿势基准数据集的实证测试。另外，我们在通常用于姿态估计的数据集上测试我们的方法，并使用深度姿态方法开始缩小差距。我们开源了我们的培训和测试代码，并且发布了可以在https网址上找到的预先训练好的模型

##### URL
[https://arxiv.org/abs/1710.00925](https://arxiv.org/abs/1710.00925)

##### PDF
[https://arxiv.org/pdf/1710.00925](https://arxiv.org/pdf/1710.00925)

