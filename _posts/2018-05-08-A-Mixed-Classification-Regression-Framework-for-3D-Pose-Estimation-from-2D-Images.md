---
layout: post
title: "A Mixed Classification-Regression Framework for 3D Pose Estimation from 2D Images"
date: 2018-05-08 18:32:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Classification
author: Siddharth Mahendran, Haider Ali, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
3D pose estimation from a single 2D image is an important and challenging task in computer vision with applications in autonomous driving, robot manipulation and augmented reality. Since 3D pose is a continuous quantity, a natural formulation for this task is to solve a pose regression problem. However, since pose regression methods return a single estimate of the pose, they have difficulties handling multimodal pose distributions (e.g. in the case of symmetric objects). An alternative formulation, which can capture multimodal pose distributions, is to discretize the pose space into bins and solve a pose classification problem. However, pose classification methods can give large pose estimation errors depending on the coarseness of the discretization. In this paper, we propose a mixed classification-regression framework that uses a classification network to produce a discrete multimodal pose estimate and a regression network to produce a continuous refinement of the discrete estimate. The proposed framework can accommodate different architectures and loss functions, leading to multiple classification-regression models, some of which achieve state-of-the-art performance on the challenging Pascal3D+ dataset.

##### Abstract (translated by Google)
来自单个2D图像的3D姿态估计是计算机视觉中的一项重要和具有挑战性的任务，应用于自动驾驶，机器人操纵和增强现实。由于3D姿态是一个连续的量，因此这个任务的一个自然表达式就是解决姿态回归问题。然而，由于姿态回归方法返回姿态的单个估计，所以它们在处理多模态姿态分布（例如，在对称对象的情况下）时存在困难。一种可以捕获多模式姿态分布的替代公式是将姿态空间离散成箱并解决姿态分类问题。然而，取决于离散化的粗糙度，姿势分类方法会给出大的姿态估计误差。在本文中，我们提出了一种混合分类回归框架，该框架使用分类网络来产生离散多模态姿态估计和回归网络，以产生离散估计的连续精化。所提出的框架可以适应不同的体系结构和损失函数，从而产生多个分类回归模型，其中一些模型在具有挑战性的Pascal3D +数据集上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1805.03225](http://arxiv.org/abs/1805.03225)

##### PDF
[http://arxiv.org/pdf/1805.03225](http://arxiv.org/pdf/1805.03225)

