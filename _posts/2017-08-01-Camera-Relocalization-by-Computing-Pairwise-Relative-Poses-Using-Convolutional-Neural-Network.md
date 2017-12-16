---
layout: post
title: "Camera Relocalization by Computing Pairwise Relative Poses Using Convolutional Neural Network"
date: 2017-08-01 10:50:39
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Deep_Learning
author: Zakaria Laskar, Iaroslav Melekhov, Surya Kalia, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new deep learning based approach for camera relocalization. Our approach localizes a given query image by using a convolutional neural network (CNN) for first retrieving similar database images and then predicting the relative pose between the query and the database images, whose poses are known. The camera location for the query image is obtained via triangulation from two relative translation estimates using a RANSAC based approach. Each relative pose estimate provides a hypothesis for the camera orientation and they are fused in a second RANSAC scheme. The neural network is trained for relative pose estimation in an end-to-end manner using training image pairs. In contrast to previous work, our approach does not require scene-specific training of the network, which improves scalability, and it can also be applied to scenes which are not available during the training of the network. As another main contribution, we release a challenging indoor localisation dataset covering 5 different scenes registered to a common coordinate frame. We evaluate our approach using both our own dataset and the standard 7 Scenes benchmark. The results show that the proposed approach generalizes well to previously unseen scenes and compares favourably to other recent CNN-based methods.

##### Abstract (translated by Google)
我们提出了一种新的基于深度学习的相机重新定位方法。我们的方法通过使用卷积神经网络（CNN）来定位给定的查询图像，以首先检索类似的数据库图像，然后预测查询和数据库图像之间的姿势已知的相对姿态。查询图像的相机位置是通过使用基于RANSAC的方法的两个相对平移估计的三角测量而获得的。每个相对姿态估计提供了相机定向的假设，并且它们在第二RANSAC方案中被融合。使用训练图像对以端对端的方式对神经网络进行相对姿态估计的训练。与以前的工作相比，我们的方法不需要对网络进行特定场景的训练，这提高了可扩展性，也可以应用于在网络训练期间不可用的场景。作为另一个主要贡献，我们发布了一个具有挑战性的室内定位数据集，涵盖了登录到共同坐标系的5个不同场景我们使用我们自己的数据集和标准的7场景基准评估我们的方法。结果表明，提出的方法很好地适用于以前未曾见过的场景，并与其他最近的基于CNN的方法相比。

##### URL
[https://arxiv.org/abs/1707.09733](https://arxiv.org/abs/1707.09733)

##### PDF
[https://arxiv.org/pdf/1707.09733](https://arxiv.org/pdf/1707.09733)

