---
layout: post
title: "Test-time augmentation with uncertainty estimation for deep learning-based medical image segmentation"
date: 2018-07-19 11:58:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Prediction Recognition
author: Guotai Wang, Wenqi Li, Michael Aertsen, Jan Deprest, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Data augmentation has been widely used for training deep learning systems for medical image segmentation and plays an important role in obtaining robust and transformation-invariant predictions. However, it has seldom been used at test time for segmentation and not been formulated in a consistent mathematical framework. In this paper, we first propose a theoretical formulation of test-time augmentation for deep learning in image recognition, where the prediction is obtained through estimating its expectation by Monte Carlo simulation with prior distributions of parameters in an image acquisition model that involves image transformations and noise. We then propose a novel uncertainty estimation method based on the formulated test-time augmentation. Experiments with segmentation of fetal brains and brain tumors from 2D and 3D Magnetic Resonance Images (MRI) showed that 1) our test-time augmentation outperforms a single-prediction baseline and dropout-based multiple predictions, and 2) it provides a better uncertainty estimation than calculating the model-based uncertainty alone and helps to reduce overconfident incorrect predictions.

##### Abstract (translated by Google)
数据增强已被广泛用于训练用于医学图像分割的深度学习系统，并且在获得稳健和变换不变预测中起重要作用。但是，它很少在测试时用于分割，而没有在一致的数学框架中制定。在本文中，我们首先提出了一种用于图像识别深度学习的测试时间增强的理论公式，其中通过蒙特卡罗模拟估计其预期来获得预测，其中参数的先前分布涉及图像变换和图像采集模型。噪声。然后，我们提出了一种基于公式化测试时间增长的新型不确定性估计方法。从2D和3D磁共振图像（MRI）分割胎儿脑和脑肿瘤的实验表明，1）我们的测试时间增加优于单预测基线和基于丢失的多重预测，2）它提供了更好的不确定性估计而不仅仅是计算基于模型的不确定性，有助于减少过度自信的错误预测。

##### URL
[https://arxiv.org/abs/1807.07356](https://arxiv.org/abs/1807.07356)

##### PDF
[https://arxiv.org/pdf/1807.07356](https://arxiv.org/pdf/1807.07356)

