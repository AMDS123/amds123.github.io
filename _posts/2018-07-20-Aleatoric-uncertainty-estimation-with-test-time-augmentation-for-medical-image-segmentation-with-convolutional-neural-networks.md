---
layout: post
title: "Aleatoric uncertainty estimation with test-time augmentation for medical image segmentation with convolutional neural networks"
date: 2018-07-20 08:26:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Guotai Wang, Wenqi Li, Michael Aertsen, Jan Deprest, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the state-of-the-art performance for medical image segmentation, deep convolutional neural networks (CNNs) have rarely provided uncertainty estimations regarding their segmentation outputs, e.g., model (epistemic) and image-based (aleatoric) uncertainties. In this work, we analyze these different types of uncertainties for CNN-based 2D and 3D medical image segmentation tasks. We additionally propose a test-time augmentation-based aleatoric uncertainty to analyze the effect of different transformations of the input image on the segmentation output. Test-time augmentation has been previously used to improve segmentation accuracy, yet not been formulated in a consistent mathematical framework. Hence, we also propose a theoretical formulation of test-time augmentation, where a distribution of the prediction is estimated by Monte Carlo simulation with prior distributions of parameters in an image acquisition model that involves image transformations and noise. We compare and combine our proposed aleatoric uncertainty with model uncertainty. Experiments with segmentation of fetal brains and brain tumors from 2D and 3D Magnetic Resonance Images (MRI) showed that 1) the test-time augmentation-based aleatoric uncertainty provides a better uncertainty estimation than calculating the test-time dropout-based model uncertainty alone and helps to reduce overconfident incorrect predictions, and 2) our test-time augmentation outperforms a single-prediction baseline and dropout-based multiple predictions.

##### Abstract (translated by Google)
尽管医学图像分割具有最先进的性能，但深度卷积神经网络（CNN）很少提供关于其分割输出的不确定性估计，例如模型（认知）和基于图像（任意）的不确定性。在这项工作中，我们分析了基于CNN的2D和3D医学图像分割任务的这些不同类型的不确定性。我们还提出了基于测试时间增强的任意不确定性来分析输入图像的不同变换对分割输出的影响。之前已经使用测试时间增强来提高分割准确度，但尚未在一致的数学框架中进行公式化。因此，我们还提出了测试时间增强的理论公式，其中通过蒙特卡罗模拟估计预测的分布，其中图像采集模型中的参数的先前分布涉及图像变换和噪声。我们比较并结合我们提出的任意不确定性与模型不确定性。从2D和3D磁共振图像（MRI）分割胎儿脑和脑肿瘤的实验表明，1）基于测试时间增强的任意不确定性提供了比单独计算基于测试时间丢失的模型不确定性更好的不确定性估计。有助于减少过度自信的错误预测，2）我们的测试时间增加优于单预测基线和基于丢失的多重预测。

##### URL
[http://arxiv.org/abs/1807.07356](http://arxiv.org/abs/1807.07356)

##### PDF
[http://arxiv.org/pdf/1807.07356](http://arxiv.org/pdf/1807.07356)

