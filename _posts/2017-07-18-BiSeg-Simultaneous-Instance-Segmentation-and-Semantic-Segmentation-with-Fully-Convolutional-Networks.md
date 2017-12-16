---
layout: post
title: "BiSeg: Simultaneous Instance Segmentation and Semantic Segmentation with Fully Convolutional Networks"
date: 2017-07-18 02:28:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Viet-Quoc Pham, Satoshi Ito, Tatsuo Kozakaya
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and effective framework for simultaneous semantic segmentation and instance segmentation with Fully Convolutional Networks (FCNs). The method, called BiSeg, predicts instance segmentation as a posterior in Bayesian inference, where semantic segmentation is used as a prior. We extend the idea of position-sensitive score maps used in recent methods to a fusion of multiple score maps at different scales and partition modes, and adopt it as a robust likelihood for instance segmentation inference. As both Bayesian inference and map fusion are performed per pixel, BiSeg is a fully convolutional end-to-end solution that inherits all the advantages of FCNs. We demonstrate state-of-the-art instance segmentation accuracy on PASCAL VOC.

##### Abstract (translated by Google)
我们提出了一个简单而有效的框架，用于完全卷积网络（FCNs）的同时语义分割和实例分割。该方法称为BiSeg，将实例分割预测为贝叶斯推理中的后验，其中语义分割被用作先验分类。我们将最近的方法中使用的位置敏感分数图的思想扩展到不同尺度和分割模式下的多个分数图的融合，并将其作为例如分割推断的鲁棒可能性。由于贝叶斯推理和地图融合都是按像素执行的，因此BiSeg是一种完全卷积的端到端解决方案，它继承了FCN的所有优点。我们在PASCAL VOC上展示了最先进的实例分割精度。

##### URL
[https://arxiv.org/abs/1706.02135](https://arxiv.org/abs/1706.02135)

##### PDF
[https://arxiv.org/pdf/1706.02135](https://arxiv.org/pdf/1706.02135)

