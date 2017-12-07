---
layout: post
title: "An Analysis of Scale Invariance in Object Detection - SNIP"
date: 2017-11-22 09:30:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Bharat Singh, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
An analysis of different techniques for recognizing and detecting objects under extreme scale variation is presented. Scale specific and scale invariant design of detectors are compared by training them with different configurations of input data. To examine if upsampling images is necessary for detecting small objects, we evaluate the performance of different network architectures for classifying small objects on ImageNet. Based on this analysis, we propose a deep end-to-end trainable Image Pyramid Network for object detection which operates on the same image scales during training and inference. Since small and large objects are difficult to recognize at smaller and larger scales respectively, we present a novel training scheme called Scale Normalization for Image Pyramids (SNIP) which selectively back-propagates the gradients of object instances of different sizes as a function of the image scale. On the COCO dataset, our single model performance is 45.7% and an ensemble of 3 networks obtains an mAP of 48.3%. We use ImageNet-1000 pre-trained models and only train with bounding box supervision. Our submission won the Best Student Entry in the COCO 2017 challenge. Code will be made available at this http URL

##### Abstract (translated by Google)
提出了在极端尺度变化下识别和检测物体的不同技术的分析。通过训练不同的输入数据配置来比较探测器的比例尺和比例不变设计。为了检查上采样图像是否需要检测小物体，我们评估了不同网络架构在ImageNet上对小物体进行分类的性能。基于这一分析，我们提出了一个深度端到端的可训练图像金字塔网络，用于在训练和推理过程中以相同的图像尺度运行的对象检测。由于小尺寸和大尺寸的物体分别在较小和较大的尺度上难以识别，因此我们提出了一种称为图像金字塔（Scale Pyramids，SNIP）的尺度标准化（Scale Normalization）的新型训练方案，该方案选择性地将作为图像的函数的不同尺寸的对象实例的梯度规模。在COCO数据集上，我们的单个模型性能是45.7％，3个网络的集合获得了48.3％的mAP。我们使用ImageNet-1000预先训练的模型，并且只使用边界框监督训练。我们的提交在COCO 2017挑战赛中赢得了最佳学生入围奖。代码将在这个http URL中提供

##### URL
[https://arxiv.org/abs/1711.08189](https://arxiv.org/abs/1711.08189)

##### PDF
[https://arxiv.org/pdf/1711.08189](https://arxiv.org/pdf/1711.08189)

