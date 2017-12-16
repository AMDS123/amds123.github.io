---
layout: post
title: "Adversarial Attacks Beyond the Image Space"
date: 2017-11-21 01:56:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Classification Prediction VQA
author: Xiaohui Zeng, Chenxi Liu, Yu-Siang Wang, Weichao Qiu, Lingxi Xie, Yu-Wing Tai, Chi Keung Tang, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Generating adversarial examples is an intriguing problem and an important way of understanding the working mechanism of deep neural networks. Recently, it has attracted a lot of attention in the computer vision community. Most existing approaches generated perturbations in image space, i.e., each pixel can be modified independently. However, it remains unclear whether these adversarial examples are authentic, in the sense that they correspond to actual changes in physical properties. This paper aims at exploring this topic in the contexts of object classification and visual question answering. The baselines are set to be several state-of-the-art deep neural networks which receive 2D input images. We augment these networks with a differentiable 3D rendering layer in front, so that a 3D scene (in physical space) is rendered into a 2D image (in image space), and then mapped to a prediction (in output space). There are two (direct or indirect) ways of attacking the physical parameters. The former back-propagates the gradients of error signals from output space to physical space directly, while the latter first constructs an adversary in image space, and then attempts to find the best solution in physical space that is rendered into this image. An important finding is that attacking physical space is much more difficult, as the direct method, compared with that used in image space, produces a much lower success rate and requires heavier perturbations to be added. On the other hand, the indirect method does not work out, suggesting that adversaries generated in image space are inauthentic. By interpreting them in physical space, most of these adversaries can be filtered out, showing promise in defending adversaries.

##### Abstract (translated by Google)
生成敌对的例子是一个有趣的问题，也是理解深度神经网络工作机制的重要途径。近来在计算机视觉领域引起了很多的关注。大多数现有的方法在图像空间中产生扰动，即，每个像素可以被独立地修改。但是，这些对抗性的例子是否真实，还是不清楚的，因为它们与物理性质的实际变化是一致的。本文旨在在对象分类和视觉问答的背景下探讨这个话题。基线设置为接收2D输入图像的多个最新的深度神经网络。我们用前面的可微3D渲染层来增强这些网络，使得3D场景（在物理空间中）被渲染成2D图像（在图像空间中），然后映射到预测（在输出空间中）。有两种（直接或间接的）攻击物理参数的方法。前者将输出空间中的误差信号的梯度直接反向传播到物理空间，而后者则首先在图像空间中构造一个对手，然后尝试在物理空间中找到最佳的解决方案。一个重要的发现是，攻击物理空间要困难得多，因为与图像空间中使用的直接方法相比，直接方法产生的成功率要低得多，并且需要添加较重的扰动。另一方面，间接方法并不成功，这表明在图像空间中产生的对手是不真实的。通过在实体空间中解读这些对手，这些对手中的绝大多数都可以被过滤出来，显示出对抗对手的承诺。

##### URL
[https://arxiv.org/abs/1711.07183](https://arxiv.org/abs/1711.07183)

##### PDF
[https://arxiv.org/pdf/1711.07183](https://arxiv.org/pdf/1711.07183)

