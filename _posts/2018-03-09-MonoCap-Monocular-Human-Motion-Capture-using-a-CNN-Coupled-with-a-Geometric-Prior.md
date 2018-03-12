---
layout: post
title: "MonoCap: Monocular Human Motion Capture using a CNN Coupled with a Geometric Prior"
date: 2018-03-09 09:28:11
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference Deep_Learning
author: Xiaowei Zhou, Menglong Zhu, Georgios Pavlakos, Spyridon Leonardos, Kostantinos G. Derpanis, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering 3D full-body human pose is a challenging problem with many applications. It has been successfully addressed by motion capture systems with body worn markers and multiple cameras. In this paper, we address the more challenging case of not only using a single camera but also not leveraging markers: going directly from 2D appearance to 3D geometry. Deep learning approaches have shown remarkable abilities to discriminatively learn 2D appearance features. The missing piece is how to integrate 2D, 3D and temporal information to recover 3D geometry and account for the uncertainties arising from the discriminative model. We introduce a novel approach that treats 2D joint locations as latent variables whose uncertainty distributions are given by a deep fully convolutional neural network. The unknown 3D poses are modeled by a sparse representation and the 3D parameter estimates are realized via an Expectation-Maximization algorithm, where it is shown that the 2D joint location uncertainties can be conveniently marginalized out during inference. Extensive evaluation on benchmark datasets shows that the proposed approach achieves greater accuracy over state-of-the-art baselines. Notably, the proposed approach does not require synchronized 2D-3D data for training and is applicable to "in-the-wild" images, which is demonstrated with the MPII dataset.

##### Abstract (translated by Google)
恢复3D全身人体姿势对于许多应用来说是一个具有挑战性的问题。运动捕捉系统已经成功解决了身体磨损标记和多个摄像头的问题。在本白皮书中，我们解决了更具挑战性的情况：不仅使用单个相机，而且不使用标记：从2D外观直接转到3D几何。深度学习方法显示出了显着的差异化学习2D外观特征的能力。缺失的部分是如何整合二维，三维和时间信息来恢复三维几何图形，并解决由区分模型引起的不确定性。我们引入了一种新颖的方法，将二维关节位置视为潜在变量，其不确定性分布由深度完全卷积神经网络给出。未知3D姿态通过稀疏表示来建模，并且3D参数估计通过期望最大化算法来实现，其中显示在推断期间2D联合位置不确定性可以方便地被排除在外。基准数据集的广泛评估表明，所提出的方法比现有技术的基线具有更高的准确性。值得注意的是，所提出的方法不需要用于训练的同步2D-3D数据，并且适用于用MPII数据集演示的“野外”图像。

##### URL
[http://arxiv.org/abs/1701.02354](http://arxiv.org/abs/1701.02354)

##### PDF
[http://arxiv.org/pdf/1701.02354](http://arxiv.org/pdf/1701.02354)

