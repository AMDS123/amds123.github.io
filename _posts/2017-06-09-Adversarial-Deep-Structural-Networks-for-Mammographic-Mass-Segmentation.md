---
layout: post
title: "Adversarial Deep Structural Networks for Mammographic Mass Segmentation"
date: 2017-06-09 21:32:38
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Classification Detection
author: Wentao Zhu, Xiang Xiang, Trac D. Tran, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Mass segmentation is an important task in mammogram analysis, providing effective morphological features and regions of interest (ROI) for mass detection and classification. Inspired by the success of using deep convolutional features for natural image analysis and conditional random fields (CRF) for structural learning, we propose an end-to-end network for mammographic mass segmentation. The network employs a fully convolutional network (FCN) to model potential function, followed by a CRF to perform structural learning. Because the mass distribution varies greatly with pixel position, the FCN is combined with position priori for the task. Due to the small size of mammogram datasets, we use adversarial training to control over-fitting. Four models with different convolutional kernels are further fused to improve the segmentation results. Experimental results on two public datasets, INbreast and DDSM-BCRP, show that our end-to-end network combined with adversarial training achieves the-state-of-the-art results.

##### Abstract (translated by Google)
质量分割是乳房X线摄影分析中的一项重要任务，为质量检测和分类提供了有效的形态特征和感兴趣区域（ROI）。受深度卷积特征用于自然图像分析和条件随机场（CRF）结构学习的成功启发，我们提出了一个端到端的乳腺摄影团块分割网络。网络采用完全卷积网络（FCN）对潜在功能进行建模，然后使用CRF进行结构化学习。由于质量分布随像素位置而变化很大，因此FCN与任务的位置先验相结合。由于乳房X线摄影数据集的尺寸较小，我们使用对抗训练来控制过度拟合。四个不同的卷积核模型进一步融合，以改善分割结果。两个公共数据集INbreast和DDSM-BCRP的实验结果表明，我们的端到端网络与对抗训练相结合，可以达到最新的结果。

##### URL
[https://arxiv.org/abs/1612.05970](https://arxiv.org/abs/1612.05970)

##### PDF
[https://arxiv.org/pdf/1612.05970](https://arxiv.org/pdf/1612.05970)

