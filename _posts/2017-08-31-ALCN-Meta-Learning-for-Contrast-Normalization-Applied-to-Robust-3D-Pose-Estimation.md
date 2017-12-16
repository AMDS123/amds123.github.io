---
layout: post
title: "ALCN: Meta-Learning for Contrast Normalization Applied to Robust 3D Pose Estimation"
date: 2017-08-31 09:28:23
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Mahdi Rad, Peter M. Roth, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
To be robust to illumination changes when detecting objects in images, the current trend is to train a Deep Network with training images captured under many different lighting conditions. Unfortunately, creating such a training set is very cumbersome, or sometimes even impossible, for some applications such as 3D pose estimation of specific objects, which is the application we focus on in this paper. We therefore propose a novel illumination normalization method that lets us learn to detect objects and estimate their 3D pose under challenging illumination conditions from very few training samples. Our key insight is that normalization parameters should adapt to the input image. In particular, we realized this via a Convolutional Neural Network trained to predict the parameters of a generalization of the Difference-of-Gaussians method. We show that our method significantly outperforms standard normalization methods and demonstrate it on two challenging 3D detection and pose estimation problems.

##### Abstract (translated by Google)
为了在检测图像中的物体时对光照变化具有鲁棒性，目前的趋势是训练具有在许多不同照明条件下捕获的训练图像的深度网络。不幸的是，创建这样的训练集对于某些应用程序（如特定对象的3D姿态估计）是非常麻烦的，有时甚至是不可能的，这是我们在本文中重点讨论的应用程序。因此，我们提出了一种新颖的照明标准化方法，使我们能够从极少的训练样本中学习在具有挑战性的照明条件下检测物体并估计其3D姿态。我们的关键洞察是归一化参数应该适应输入图像。特别是，我们通过一个卷积神经网络来实现这一点，这个网络被训练来预测高斯差分法的泛化参数。我们表明，我们的方法明显优于标准的规范化方法，并在两个具有挑战性的3D检测和姿态估计问题上展示它。

##### URL
[https://arxiv.org/abs/1708.09633](https://arxiv.org/abs/1708.09633)

##### PDF
[https://arxiv.org/pdf/1708.09633](https://arxiv.org/pdf/1708.09633)

