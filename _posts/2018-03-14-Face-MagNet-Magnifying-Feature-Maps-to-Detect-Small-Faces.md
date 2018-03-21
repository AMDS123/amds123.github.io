---
layout: post
title: "Face-MagNet: Magnifying Feature Maps to Detect Small Faces"
date: 2018-03-14 13:22:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Pouya Samangouei, Mahyar Najibi, Larry Davis, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the Face Magnifier Network (Face-MageNet), a face detector based on the Faster-RCNN framework which enables the flow of discriminative information of small scale faces to the classifier without any skip or residual connections. To achieve this, Face-MagNet deploys a set of ConvTranspose, also known as deconvolution, layers in the Region Proposal Network (RPN) and another set before the Region of Interest (RoI) pooling layer to facilitate detection of finer faces. In addition, we also design, train, and evaluate three other well-tuned architectures that represent the conventional solutions to the scale problem: context pooling, skip connections, and scale partitioning. Each of these three networks achieves comparable results to the state-of-the-art face detectors. With extensive experiments, we show that Face-MagNet based on a VGG16 architecture achieves better results than the recently proposed ResNet101-based HR method on the task of face detection on WIDER dataset and also achieves similar results on the hard set as our other method SSH.

##### Abstract (translated by Google)
在本文中，我们介绍面部放大器网络（Face-MageNet），它是一种基于Faster-RCNN框架的人脸检测器，它可以将小尺度人脸的识别信息流传送给分类器，而不会有任何跳跃或残留连接。为此，Face-MagNet在区域提议网络（RPN）中部署了一组ConvTranspose（也称为去卷积）层，并在感兴趣区域（RoI）池层之前部署了另一组ConvTranspose层，以便检测更精细的人脸。此外，我们还设计，培训和评估其他三个精心设计的架构，这些架构代表了规模问题的常规解决方案：上下文池，跳过连接和缩放分区。这三个网络中的每一个都可以获得与最先进的面部检测器相媲美的结果。经过大量实验，我们证明基于VGG16架构的Face-MagNet比最近提出的基于ResNet101的HR方法在WIDER数据集上的人脸检测任务上获得了更好的结果，并且在硬件集上也获得了与我们的其他方法SSH类似的结果。

##### URL
[https://arxiv.org/abs/1803.05258](https://arxiv.org/abs/1803.05258)

##### PDF
[https://arxiv.org/pdf/1803.05258](https://arxiv.org/pdf/1803.05258)

