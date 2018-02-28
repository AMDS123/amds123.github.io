---
layout: post
title: "Recurrent Residual Module for Fast Inference in Videos"
date: 2018-02-27 05:25:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Inference Detection Recognition
author: Bowen Pan, Wuwei Lin, Xiaolin Fang, Chaoqin Huang, Bolei Zhou, Cewu Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have made impressive progress in many video recognition tasks such as video pose estimation and video object detection. However, CNN inference on video is computationally expensive due to processing dense frames individually. In this work, we propose a framework called Recurrent Residual Module (RRM) to accelerate the CNN inference for video recognition tasks. This framework has a novel design of using the similarity of the intermediate feature maps of two consecutive frames, to largely reduce the redundant computation. One unique property of the proposed method compared to previous work is that feature maps of each frame are precisely computed. The experiments show that, while maintaining the similar recognition performance, our RRM yields averagely 2x acceleration on the commonly used CNNs such as AlexNet, ResNet, deep compression model (thus 8-12x faster than the original dense models using the efficient inference engine), and impressively 9x acceleration on some binary networks such as XNOR-Nets (thus 500x faster than the original model). We further verify the effectiveness of the RRM on speeding up CNNs for video pose estimation and video object detection.

##### Abstract (translated by Google)
深卷积神经网络（CNNs）在许多视频识别任务中取得了令人瞩目的进步，如视频姿态估计和视频对象检测。然而，由于单独处理密集帧，CNN对视频的推断在计算上是昂贵的。在这项工作中，我们提出了一个称为回收残余模块（RRM）的框架来加速视频识别任务的CNN推断。该框架具有使用两个连续帧的中间特征映射的相似性的新颖设计，以大大减少冗余计算。与以前的工作相比，所提出的方法的一个独特性质是精确计算每个帧的特征映射。实验表明，在保持类似识别性能的同时，我们的RRM平均在常用CNN上产生2倍加速度，如AlexNet，ResNet，深度压缩模型（因此比使用高效推理引擎的原始密集模型快8-12倍），以及XNOR-Nets等二进制网络上9倍的加速度（因此比原始模型快500倍）。我们进一步验证了RRM在加速CNN进行视频姿态估计和视频对象检测方面的有效性。

##### URL
[https://arxiv.org/abs/1802.09723](https://arxiv.org/abs/1802.09723)

##### PDF
[https://arxiv.org/pdf/1802.09723](https://arxiv.org/pdf/1802.09723)

