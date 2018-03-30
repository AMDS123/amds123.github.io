---
layout: post
title: "3D Human Pose Estimation in the Wild by Adversarial Learning"
date: 2018-03-26 17:24:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation CNN
author: Wei Yang, Wanli Ouyang, Xiaolong Wang, Jimmy Ren, Hongsheng Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, remarkable advances have been achieved in 3D human pose estimation from monocular images because of the powerful Deep Convolutional Neural Networks (DCNNs). Despite their success on large-scale datasets collected in the constrained lab environment, it is difficult to obtain the 3D pose annotations for in-the-wild images. Therefore, 3D human pose estimation in the wild is still a challenge. In this paper, we propose an adversarial learning framework, which distills the 3D human pose structures learned from the fully annotated dataset to in-the-wild images with only 2D pose annotations. Instead of defining hard-coded rules to constrain the pose estimation results, we design a novel multi-source discriminator to distinguish the predicted 3D poses from the ground-truth, which helps to enforce the pose estimator to generate anthropometrically valid poses even with images in the wild. We also observe that a carefully designed information source for the discriminator is essential to boost the performance. Thus, we design a geometric descriptor, which computes the pairwise relative locations and distances between body joints, as a new information source for the discriminator. The efficacy of our adversarial learning framework with the new geometric descriptor has been demonstrated through extensive experiments on widely used public benchmarks. Our approach significantly improves the performance compared with previous state-of-the-art approaches.

##### Abstract (translated by Google)
最近，由于具有强大的深度卷积神经网络（DCNN），单眼图像的三维人体姿态估计取得了显着的进步。尽管他们在受限实验室环境中收集的大型数据集上取得了成功，但很难获得用于野外图像的3D姿态注释。因此，野外3D人体姿势估算仍然是一个挑战。在本文中，我们提出了一种敌对学习框架，该框架将从完全注释的数据集中学习的三维人体姿态结构提取到只有2D姿态注释的野外图像中。我们设计了一种新颖的多源识别器来区分预测的3D姿势和地面实况，而不是定义硬编码的规则来约束姿态估计结果，这有助于强制姿态估计器生成人体测量学有效的姿势，即使图像狂野。我们还观察到，鉴别器的精心设计的信息源对提高性能至关重要。因此，我们设计了一个几何描述符，它计算身体关节之间的成对相对位置和距离，作为鉴别器的新信息源。通过广泛使用的广泛使用的公共基准进行了广泛的实验，证明了我们的具有新几何描述符的敌对学习框架的功效。与先前的最先进方法相比，我们的方法显着提高了性能。

##### URL
[https://arxiv.org/abs/1803.09722](https://arxiv.org/abs/1803.09722)

##### PDF
[https://arxiv.org/pdf/1803.09722](https://arxiv.org/pdf/1803.09722)

