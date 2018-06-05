---
layout: post
title: "Real-time Deep Pose Estimation with Geodesic Loss for Image-to-Template Rigid Registration"
date: 2018-06-03 20:11:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation Optimization Deep_Learning
author: Seyed Sadegh Mohseni Salehi, Shadab Khan, Deniz Erdogmus, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
With an aim to increase the capture range and accelerate the performance of state-of-the-art inter-subject and subject-to-template 3D registration, we propose deep learning-based methods that are trained to find the 3D position of arbitrarily oriented subjects or anatomy based on slices or volumes of medical images. For this, we propose regression CNNs that learn to predict the angle-axis representation of 3D rotations and translations using image features. We use and compare mean square error and geodesic loss to train regression CNNs for 3D pose estimation used in two different scenarios: slice-to-volume registration and volume-to-volume registration. Our results show that in such registration applications that are amendable to learning, the proposed deep learning methods with geodesic loss minimization can achieve accurate results with a wide capture range in real-time (&lt;100ms). We also tested the generalization capability of the trained CNNs on an expanded age range and on images of newborn subjects with similar and different MR image contrasts. We trained our models on T2-weighted fetal brain MRI scans and used them to predict the 3D pose of newborn brains based on T1-weighted MRI scans. We showed that the trained models generalized well for the new domain when we performed image contrast transfer through a conditional generative adversarial network. This indicates that the domain of application of the trained deep regression CNNs can be further expanded to image modalities and contrasts other than those used in training. A combination of our proposed methods with accelerated optimization-based registration algorithms can dramatically enhance the performance of automatic imaging devices and image processing methods of the future.

##### Abstract (translated by Google)
为了增加捕获范围并加速最先进的主题间和主题到模板的3D注册的表现，我们提出了深度学习的方法，这些方法经过训练以找到任意取向的3D位置基于医学图像的切片或体积的受试者或解剖结构。为此，我们建议回归CNNs，学习使用图像特征来预测3D旋转和平移的角度轴表示。我们使用并比较均方误差和测地线损失来训练用于两种不同情况下的三维姿态估计的回归CNN：切片对卷注册和卷对卷注册。我们的结果表明，在这种可修改为学习的注册应用中，具有测地损失最小化的所提出的深度学习方法可以实现具有实时（<100ms）的宽捕捉范围的准确结果。我们还测试了经过培训的CNN在扩大年龄范围内的泛化能力以及具有类似和不同MR图像对比度的新生儿受试者的图像。我们在T2加权胎儿脑MRI扫描上训练了我们的模型，并使用它们基于T1加权MRI扫描来预测新生大脑的3D姿态。我们表明，当我们通过有条件的生成对抗网络进行图像对比度转换时，训练好的模型对于新的领域具有良好的推广能力。这表明经过训练的深回归CNN的应用领域可以进一步扩展到训练中使用的图像模态和对比度。我们提出的方法与基于加速优化的配准算法的组合可以显着提高未来自动成像设备和图像处理方法的性能。

##### URL
[http://arxiv.org/abs/1803.05982](http://arxiv.org/abs/1803.05982)

##### PDF
[http://arxiv.org/pdf/1803.05982](http://arxiv.org/pdf/1803.05982)

