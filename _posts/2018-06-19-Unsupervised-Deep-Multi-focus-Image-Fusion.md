---
layout: post
title: "Unsupervised Deep Multi-focus Image Fusion"
date: 2018-06-19 14:15:47
categories: arXiv_CV
tags: arXiv_CV CNN
author: Xiang Yan, Syed Zulqarnain Gilani, Hanlin Qin, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have recently been used for multi-focus image fusion. However, due to the lack of labeled data for supervised training of such networks, existing methods have resorted to adding Gaussian blur in focused images to simulate defocus and generate synthetic training data with ground-truth for supervised learning. Moreover, they classify pixels as focused or defocused and leverage the results to construct the fusion weight maps which then necessitates a series of post-processing steps. In this paper, we present unsupervised end-to-end learning for directly predicting the fully focused output image from multi-focus input image pairs. The proposed approach uses a novel CNN architecture trained to perform fusion without the need for ground truth fused images and exploits the image structural similarity (SSIM) to calculate the loss; a metric that is widely accepted for fused image quality evaluation. Consequently, we are able to utilize {\em real} benchmark datasets, instead of simulated ones, to train our network. The model is a feed-forward, fully convolutional neural network that can process images of variable sizes during test time. Extensive evaluations on benchmark datasets show that our method outperforms existing state-of-the-art in terms of visual quality and objective evaluations.

##### Abstract (translated by Google)
卷积神经网络最近已被用于多焦点图像融合。然而，由于缺乏用于这种网络的监督训练的标记数据，现有方法已经采取在聚焦图像中添加高斯模糊来模拟散焦并且为监督学习生成具有地面实况的合成训练数据。此外，他们将像素分类为聚焦或散焦，并利用结果构建融合权重图，然后需要一系列后处理步骤。在本文中，我们提出了无监督的端到端学习，用于直接预测来自多焦点输入图像对的完全聚焦的输出图像。所提出的方法使用经过训练的新型CNN架构来执行融合，而不需要基础真实融合图像并利用图像结构相似性（SSIM）来计算损失;一种被广泛接受的融合图像质量评估指标。因此，我们能够利用{\ em real}基准数据集来代替模拟数据集来训练我们的网络。该模型是一个前馈完全卷积神经网络，可以在测试时间内处理各种大小的图像。基准数据集的广泛评估表明，我们的方法在视觉质量和客观评估方面优于现有的最新技术。

##### URL
[http://arxiv.org/abs/1806.07272](http://arxiv.org/abs/1806.07272)

##### PDF
[http://arxiv.org/pdf/1806.07272](http://arxiv.org/pdf/1806.07272)

