---
layout: post
title: "Adversarial Learning of Structure-Aware Fully Convolutional Networks for Landmark Localization"
date: 2017-11-01 08:54:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation CNN Prediction
author: Yu Chen, Chunhua Shen, Xiu-Shen Wei, Lingqiao Liu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Landmark/pose estimation in single monocular images have received much effort in computer vision due to its important applications. It remains a challenging task when input images severe occlusions caused by, e.g., adverse camera views. Under such circumstances, biologically implausible pose predictions may be produced. In contrast, human vision is able to predict poses by exploiting geometric constraints of landmark point inter-connectivity. To address the problem, by incorporating priors about the structure of pose components, we propose a novel structure-aware fully convolutional network to implicitly take such priors into account during training of the deep network. Explicit learning of such constraints is typically challenging. Instead, inspired by how human identifies implausible poses, we design discriminators to distinguish the real poses from the fake ones (such as biologically implausible ones). If the pose generator G generates results that the discriminator fails to distinguish from real ones, the network successfully learns the priors. Training of the network follows the strategy of conditional Generative Adversarial Networks (GANs). The effectiveness of the proposed network is evaluated on three pose-related tasks: 2D single human pose estimation, 2D facial landmark estimation and 3D single human pose estimation. The proposed approach significantly outperforms the state-of-the-art methods and almost always generates plausible pose predictions, demonstrating the usefulness of implicit learning of structures using GANs.

##### Abstract (translated by Google)
单目单目图像中的地标/姿态估计由于其重要的应用在计算机视觉方面已经付出了很多努力。当由于例如不利的照相机视图导致的输入图像严重遮挡时，它仍然是具有挑战性的任务。在这种情况下，可能会产生生物难以置信的姿态预测。相比之下，人类视觉能够通过利用界标点互连的几何约束来预测姿态。为了解决这个问题，通过引入关于姿态分量结构的先验知识，我们提出了一种新型的结构感知型完全卷积网络，在深度网络的训练中隐含地考虑了这种先验。对这些约束的显式学习通常是具有挑战性的。相反，受到人类如何识别难以置信的姿势的启发，我们设计鉴别者来区分真实姿势和假冒姿势（例如生物上不可信的姿势）。如果姿势发生器G产生鉴别器不能区分真实的结果，则网络成功地学习先验。网络的培训遵循有条件的生成敌对网络（GAN）的策略。所提出的网络的有效性在三个与姿势相关的任务上进行评估：2D单人姿势估计，2D面部标志估计和3D单人姿态估计。所提出的方法明显胜过最先进的方法，并且几乎总是产生合理的姿态预测，展示了使用GAN的结构的隐式学习的有用性。

##### URL
[https://arxiv.org/abs/1711.00253](https://arxiv.org/abs/1711.00253)

##### PDF
[https://arxiv.org/pdf/1711.00253](https://arxiv.org/pdf/1711.00253)

