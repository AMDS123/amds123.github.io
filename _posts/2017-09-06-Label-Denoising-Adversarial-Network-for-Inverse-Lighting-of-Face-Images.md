---
layout: post
title: "Label Denoising Adversarial Network for Inverse Lighting of Face Images"
date: 2017-09-06 20:46:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face CNN Optimization Detection
author: Hao Zhou, Jin Sun, Yaser Yacoob, David W. Jacobs
mathjax: true
---

* content
{:toc}

##### Abstract
Lighting estimation from face images is an important task and has applications in many areas such as image editing, intrinsic image decomposition, and image forgery detection. We propose to train a deep Convolutional Neural Network (CNN) to regress lighting parameters from a single face image. Lacking massive ground truth lighting labels for face images in the wild, we use an existing method to estimate lighting parameters, which are treated as ground truth with unknown noises. To alleviate the effect of such noises, we utilize the idea of Generative Adversarial Networks (GAN) and propose a Label Denoising Adversarial Network (LDAN) to make use of synthetic data with accurate ground truth to help train a deep CNN for lighting regression on real face images. Experiments show that our network outperforms existing methods in producing consistent lighting parameters of different faces under similar lighting conditions. Moreover, our method is 100,000 times faster in execution time than prior optimization-based lighting estimation approaches.

##### Abstract (translated by Google)
从人脸图像中进行光照估计是一项重要的任务，在图像编辑，本征图像分解，图像伪造检测等领域有着广泛的应用。我们建议训练一个深度的卷积神经网络（CNN），以从单个人脸图像中回归照明参数。缺乏野外面部图像的大量的地面真实照明标签，我们使用现有的方法来估计照明参数，将其视为具有未知噪声的地面真实。为了减轻这种噪声的影响，我们利用了生成对抗网络（GAN）的思想，并提出了一个标签去噪敌手网络（LDAN），利用具有准确地面真实性的合成数据来帮助训练一个深度的CNN，脸部图像。实验表明，我们的网络比同类照明条件下产生一致的不同人脸照明参数方法优于现有的方法。而且，我们的方法执行时间比现有的基于优化的照明估计方法快10万倍。

##### URL
[https://arxiv.org/abs/1709.01993](https://arxiv.org/abs/1709.01993)

##### PDF
[https://arxiv.org/pdf/1709.01993](https://arxiv.org/pdf/1709.01993)

