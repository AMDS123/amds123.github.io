---
layout: post
title: "Pose and Shape Estimation with Discriminatively Learned Parts"
date: 2015-02-01 04:09:23
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Menglong Zhu, Xiaowei Zhou, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new approach for estimating the 3D pose and the 3D shape of an object from a single image. Given a training set of view exemplars, we learn and select appearance-based discriminative parts which are mapped onto the 3D model from the training set through a facil- ity location optimization. The training set of 3D models is summarized into a sparse set of shapes from which we can generalize by linear combination. Given a test picture, we detect hypotheses for each part. The main challenge is to select from these hypotheses and compute the 3D pose and shape coefficients at the same time. To achieve this, we optimize a function that minimizes simultaneously the geometric reprojection error as well as the appearance matching of the parts. We apply the alternating direction method of multipliers (ADMM) to minimize the resulting convex function. We evaluate our approach on the Fine Grained 3D Car dataset with superior performance in shape and pose errors. Our main and novel contribution is the simultaneous solution for part localization, 3D pose and shape by maximizing both geometric and appearance compatibility.

##### Abstract (translated by Google)
我们引入了一种新的方法，用于从单个图像估计对象的三维姿态和三维形状。给定一组训练集的视图范例，我们学习并选择基于外观的区分部分，这些部分通过一个功能位置优化从训练集映射到三维模型上。将三维模型的训练集合成一个稀疏的形状集合，我们可以通过线性组合来推广。给出一个测试图片，我们检测每个部分的假设。主要的挑战是从这些假设中进行选择，同时计算3D姿态和形状系数。为了达到这个目的，我们优化了一个同时使几何重投影误差以及部件外观匹配最小化的函数。我们应用乘法器（ADMM）的交替方向方法来使得到的凸函数最小化。我们在Fine Grained 3D Car数据集上评估我们的方法，在形状和姿态方面表现出色。我们的主要和新颖的贡献是通过最大化几何和外观兼容性来同时解决零件定位，三维姿态和形状。

##### URL
[https://arxiv.org/abs/1502.00192](https://arxiv.org/abs/1502.00192)

##### PDF
[https://arxiv.org/pdf/1502.00192](https://arxiv.org/pdf/1502.00192)

