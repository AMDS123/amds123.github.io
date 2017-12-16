---
layout: post
title: "Deep Multi-scale Convolutional Neural Network for Dynamic Scene Deblurring"
date: 2016-12-07 10:08:33
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Quantitative
author: Seungjun Nah, Tae Hyun Kim, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Non-uniform blind deblurring for general dynamic scenes is a challenging computer vision problem since blurs are caused by camera shake, scene depth as well as multiple object motions. To remove these complicated motion blurs, conventional energy optimization based methods rely on simple assumptions such that blur kernel is partially uniform or locally linear. Moreover, recent machine learning based methods also depend on synthetic blur datasets generated under these assumptions. This makes conventional deblurring methods fail to remove blurs where blur kernel is difficult to approximate or parameterize (e.g. object motion boundaries). In this work, we propose a multi-scale convolutional neural network that restores blurred images caused by various sources in an end-to-end manner. Furthermore, we present multi-scale loss function that mimics conventional coarse-to-fine approaches. Moreover, we propose a new large scale dataset that provides pairs of realistic blurry image and the corresponding ground truth sharp image that are obtained by a high-speed camera. With the proposed model trained on this dataset, we demonstrate empirically that our method achieves the state-of-the-art performance in dynamic scene deblurring not only qualitatively, but also quantitatively.

##### Abstract (translated by Google)
对于一般动态场景的不均匀盲去模是一个具有挑战性的计算机视觉问题，因为模糊是由相机抖动，场景深度以及多个对象运动引起的。为了去除这些复杂的运动模糊，常规的基于能量优化的方法依赖于简单的假设，使得模糊核部分均匀或局部线性。而且，最近的基于机器学习的方法也依赖于在这些假设下生成的合成模糊数据集。这使得常规去模糊方法无法消除模糊内核难以近似或参数化（例如对象运动边界）的模糊。在这项工作中，我们提出了一个多尺度卷积神经网络，以端到端的方式恢复由各种来源引起的模糊图像。此外，我们提出了模拟传统的从粗到精的方法的多尺度损失函数。此外，我们提出了一个新的大规模数据集，提供了一对高清摄像机获得的实际模糊图像和相应的地面真实清晰图像。通过对这个数据集进行训练的模型，我们证明了我们的方法在动态场景去模糊中不仅在质量上，而且在数量上都达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1612.02177](https://arxiv.org/abs/1612.02177)

##### PDF
[https://arxiv.org/pdf/1612.02177](https://arxiv.org/pdf/1612.02177)

