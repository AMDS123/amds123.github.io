---
layout: post
title: "D-PCN: Parallel Convolutional Neural Networks for Image Recognition in Reverse Adversarial Style"
date: 2017-11-15 01:29:55
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification Prediction Recognition
author: Shiqi Yang, Gang Peng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a recognition framework named D-PCN using a discriminator is proposed, which can intensify the feature extracting ability of convolutional neural networks. The framework contains two parallel convolutional neural networks, and a discriminator, which is introduced from the Generative Adversarial Nets and can improve the performance of parallel networks. The two nets are devised side by side, and the discriminator takes in the features from parallel networks as input, aiming to guide the two nets to learn features of different details in a reverse adversarial style. After that, the feature maps from two nets get aggregated, then an extra overall classifier is added and will output the final prediction employing the fused features. The training strategy of the D-PCN is also introduced which ensures the utilization of the discriminator. We experiment the D-PCN with several CNN models including NIN, ResNet, ResNeXt and DenseNet using single NVIDIA TITAN Xp, on the two benchmark datasets: CIFAR-100 and downsampled ImageNet-1k, the D-PCN enhances all models on CIFAR-100 and also reinforces the performance of ResNet on downsampled ImageNet-1k explicitly. In particular, it yields state-of-the-art classification performance on CIFAR-100 with compared to relative works.

##### Abstract (translated by Google)
本文提出了一种基于鉴别器的识别框架D-PCN，可以加强卷积神经网络的特征提取能力。该框架包含两个并行的卷积神经网络和一个从生成敌对网络引入的鉴别器，可以提高并行网络的性能。两个网络并排设计，鉴别器以并行网络的特征为输入，旨在引导两个网络以反向对抗的方式学习不同细节的特征。之后，将两个网络的特征映射进行聚合，然后再添加一个额外的全局分类器，并输出使用融合特征的最终预测。介绍了D-PCN的训练策略，保证了鉴别器的使用。在CIFAR-100和下采样的ImageNet-1k两个基准数据集上，我们使用单个NVIDIA TITAN Xp对几个CNN模型（包括NIN，ResNet，ResNeXt和DenseNet）进行了D-PCN实验，D-PCN增强了CIFAR-100并且明确地加强了ResNet在下采样ImageNet-1k上的性能。特别是，与相关作品相比，它在CIFAR-100上获得了最先进的分类性能。

##### URL
[https://arxiv.org/abs/1711.04237](https://arxiv.org/abs/1711.04237)

##### PDF
[https://arxiv.org/pdf/1711.04237](https://arxiv.org/pdf/1711.04237)

