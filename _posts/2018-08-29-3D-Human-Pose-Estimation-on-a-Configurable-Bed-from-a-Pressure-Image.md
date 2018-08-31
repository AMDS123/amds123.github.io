---
layout: post
title: "3D Human Pose Estimation on a Configurable Bed from a Pressure Image"
date: 2018-08-29 22:30:32
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Henry M. Clever, Ariel Kapusta, Daehyung Park, Zackory Erickson, Yash Chitalia, Charles C. Kemp
mathjax: true
---

* content
{:toc}

##### Abstract
Robots have the potential to assist people in bed, such as in healthcare settings, yet bedding materials like sheets and blankets can make observation of the human body difficult for robots. A pressure-sensing mat on a bed can provide pressure images that are relatively insensitive to bedding materials. However, prior work on estimating human pose from pressure images has been restricted to 2D pose estimates and flat beds. In this work, we present two convolutional neural networks to estimate the 3D joint positions of a person in a configurable bed from a single pressure image. The first network directly outputs 3D joint positions, while the second outputs a kinematic model that includes estimated joint angles and limb lengths. We evaluated our networks on data from 17 human participants with two bed configurations: supine and seated. Our networks achieved a mean joint position error of 77 mm when tested with data from people outside the training set, outperforming several baselines. We also present a simple mechanical model that provides insight into ambiguity associated with limbs raised off of the pressure mat, and demonstrate that Monte Carlo dropout can be used to estimate pose confidence in these situations. Finally, we provide a demonstration in which a mobile manipulator uses our network's estimated kinematic model to reach a location on a person's body in spite of the person being seated in a bed and covered by a blanket.

##### Abstract (translated by Google)
机器人有可能帮助人们在床上，例如在医疗保健环境中，但床单和毯子等床上用品可以让机器人难以观察人体。床上的压力传感垫可以提供对垫料相对不敏感的压力图像。然而，先前关于从压力图像估计人体姿势的工作已限于2D姿势估计和平坦床。在这项工作中，我们提出了两个卷积神经网络，以从单个压力图像估计人在可配置床中的3D关节位置。第一个网络直接输出3D关节位置，而第二个网络输出包含估计关节角度和肢体长度的运动学模型。我们根据17名具有两种床配置的人类参与者的数据来评估我们的网络：仰卧和坐姿。当使用来自训练集之外的人的数据进行测试时，我们的网络实现了77 mm的平均关节位置误差，超过了几个基线。我们还提供了一个简单的机械模型，可以深入了解与压力垫产生的肢体相关的模糊性，并证明蒙特卡洛辍学可用于估计这些情况下的姿势置信度。最后，我们提供了一个演示，其中移动操纵器使用我们网络的估计运动模型到达人体的位置，尽管人坐在床上并被毯子覆盖。

##### URL
[http://arxiv.org/abs/1804.07873](http://arxiv.org/abs/1804.07873)

##### PDF
[http://arxiv.org/pdf/1804.07873](http://arxiv.org/pdf/1804.07873)

