---
layout: post
title: "Adversarial PoseNet: A Structure-aware Convolutional Network for Human Pose Estimation"
date: 2017-05-02 03:54:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation CNN Prediction
author: Yu Chen, Chunhua Shen, Xiu-Shen Wei, Lingqiao Liu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
For human pose estimation in monocular images, joint occlusions and overlapping upon human bodies often result in deviated pose predictions. Under these circumstances, biologically implausible pose predictions may be produced. In contrast, human vision is able to predict poses by exploiting geometric constraints of joint inter-connectivity. To address the problem by incorporating priors about the structure of human bodies, we propose a novel structure-aware convolutional network to implicitly take such priors into account during training of the deep network. Explicit learning of such constraints is typically challenging. Instead, we design discriminators to distinguish the real poses from the fake ones (such as biologically implausible ones). If the pose generator (G) generates results that the discriminator fails to distinguish from real ones, the network successfully learns the priors.

##### Abstract (translated by Google)
对于单眼图像中的人体姿态估计，人体上的关节遮挡和重叠往往导致姿态预测偏差。在这种情况下，可能会产生生物难以置信的姿态预测。相反，人类视觉能够通过利用联合互连的几何约束来预测姿态。为了解决这个问题，我们提出了一个新的结构感知卷积网络，在深度网络的训练过程中隐含地考虑了这种先验。对这些约束的显式学习通常是具有挑战性的。相反，我们设计鉴别者来区分真实姿势和假冒姿势（例如生物上不可信的姿势）。如果姿态发生器（G）产生鉴别器不能区分真实的结果，则网络成功地学习先验。

##### URL
[https://arxiv.org/abs/1705.00389](https://arxiv.org/abs/1705.00389)

##### PDF
[https://arxiv.org/pdf/1705.00389](https://arxiv.org/pdf/1705.00389)

