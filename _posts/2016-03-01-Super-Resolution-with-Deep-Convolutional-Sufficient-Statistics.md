---
layout: post
title: "Super-Resolution with Deep Convolutional Sufficient Statistics"
date: 2016-03-01 18:26:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN Prediction
author: Joan Bruna, Pablo Sprechmann, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
Inverse problems in image and audio, and super-resolution in particular, can be seen as high-dimensional structured prediction problems, where the goal is to characterize the conditional distribution of a high-resolution output given its low-resolution corrupted observation. When the scaling ratio is small, point estimates achieve impressive performance, but soon they suffer from the regression-to-the-mean problem, result of their inability to capture the multi-modality of this conditional distribution. Modeling high-dimensional image and audio distributions is a hard task, requiring both the ability to model complex geometrical structures and textured regions. In this paper, we propose to use as conditional model a Gibbs distribution, where its sufficient statistics are given by deep convolutional neural networks. The features computed by the network are stable to local deformation, and have reduced variance when the input is a stationary texture. These properties imply that the resulting sufficient statistics minimize the uncertainty of the target signals given the degraded observations, while being highly informative. The filters of the CNN are initialized by multiscale complex wavelets, and then we propose an algorithm to fine-tune them by estimating the gradient of the conditional log-likelihood, which bears some similarities with Generative Adversarial Networks. We evaluate experimentally the proposed approach in the image super-resolution task, but the approach is general and could be used in other challenging ill-posed problems such as audio bandwidth extension.

##### Abstract (translated by Google)
图像和音频中的逆问题以及特别是超分辨率问题可以被看作是高维结构化的预测问题，其目标是鉴于其低分辨率损坏的观察结果来表征高分辨率输出的条件分布。当缩放比例较小时，点估计达到了令人印象深刻的性能，但很快就遭受了回归到平均值问题，这是由于它们无法捕获这种条件分布的多模式所致。对高维图像和音频分布进行建模是一项艰巨的任务，需要对复杂的几何结构和纹理区域进行建模的能力。在本文中，我们建议使用一个吉布斯分布的条件模型，其深度卷积神经网络给出了足够的统计量。由网络计算的特征对于局部变形是稳定的，并且在输入是固定纹理时具有减小的变化。这些性质意味着由此产生的足够的统计数据使观测信号恶化的目标信号的不确定性最小化，同时具有高度的信息量。 CNN中的滤波器通过多尺度复小波初始化，然后通过估计条件对数似然的梯度来提出一种微调算法，与生成对抗网络有一定的相似性。我们在图像超分辨率任务中通过实验来评估所提出的方法，但是这种方法是通用的，并且可以用于其他具有挑战性的不适合的问题，例如音频带宽扩展。

##### URL
[https://arxiv.org/abs/1511.05666](https://arxiv.org/abs/1511.05666)

##### PDF
[https://arxiv.org/pdf/1511.05666](https://arxiv.org/pdf/1511.05666)

