---
layout: post
title: "Deep Multi-scale Convolutional Neural Network for Dynamic Scene Deblurring"
date: 2018-05-07 06:15:57
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Quantitative
author: Seungjun Nah, Tae Hyun Kim, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Non-uniform blind deblurring for general dynamic scenes is a challenging computer vision problem as blurs arise not only from multiple object motions but also from camera shake, scene depth variation. To remove these complicated motion blurs, conventional energy optimization based methods rely on simple assumptions such that blur kernel is partially uniform or locally linear. Moreover, recent machine learning based methods also depend on synthetic blur datasets generated under these assumptions. This makes conventional deblurring methods fail to remove blurs where blur kernel is difficult to approximate or parameterize (e.g. object motion boundaries). In this work, we propose a multi-scale convolutional neural network that restores sharp images in an end-to-end manner where blur is caused by various sources. Together, we present multi-scale loss function that mimics conventional coarse-to-fine approaches. Furthermore, we propose a new large-scale dataset that provides pairs of realistic blurry image and the corresponding ground truth sharp image that are obtained by a high-speed camera. With the proposed model trained on this dataset, we demonstrate empirically that our method achieves the state-of-the-art performance in dynamic scene deblurring not only qualitatively, but also quantitatively.

##### Abstract (translated by Google)
对于一般动态场景的非均匀盲去模是一个具有挑战性的计算机视觉问题，因为模糊不仅来自多个对象运动，而且来自相机抖动，场景深度变化。为了去除这些复杂的运动模糊，基于常规能量优化的方法依赖于简单的假设，使得模糊核心部分均匀或局部线性。此外，最近的基于机器学习的方法也依赖于在这些假设下生成的合成模糊数据集。这使得常规去模糊方法无法消除模糊内核难以近似或参数化（例如对象运动边界）的模糊。在这项工作中，我们提出了一种多尺度卷积神经网络，可以以各种来源造成模糊的端对端方式恢复清晰的图像。总之，我们提出了模拟传统的从粗到精的方法的多尺度损失函数。此外，我们提出了一个新的大规模数据集，它提供了由高速摄像机获得的实际模糊图像和相应的基本真实清晰图像对。通过对这个数据集进行训练的模型，我们凭经验证明，我们的方法不仅在定性上，而且在数量上实现了动态场景去模糊的最新性能。

##### URL
[http://arxiv.org/abs/1612.02177](http://arxiv.org/abs/1612.02177)

##### PDF
[http://arxiv.org/pdf/1612.02177](http://arxiv.org/pdf/1612.02177)

