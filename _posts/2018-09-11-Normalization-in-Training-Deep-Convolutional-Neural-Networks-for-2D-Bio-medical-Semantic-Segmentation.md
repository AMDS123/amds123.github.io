---
layout: post
title: "Normalization in Training Deep Convolutional Neural Networks for 2D Bio-medical Semantic Segmentation"
date: 2018-09-11 10:27:45
categories: arXiv_CV
tags: arXiv_CV Review Segmentation CNN Semantic_Segmentation
author: Xiao-Yun Zhou, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
2D bio-medical semantic segmentation is important for surgical robotic vision. Segmentation methods based on Deep Convolutional Neural Network (DCNN) out-perform conventional methods in terms of both the accuracy and automation. One common issue in training DCNN is the internal covariate shift, where the convolutional kernels are trained to fit the distribution change of input feature, hence both the training speed and performance are decreased. Batch Normalization (BN) is the first proposed method for addressing internal covariate shift and is widely used. Later Instance Normalization (IN) and Layer Normalization (LN) were proposed and are used much less than BN. Group Normalization (GN) was proposed very recently and has not been applied into 2D bio-medical semantic segmentation yet. Most DCNN-based bio-medical semantic segmentation adopts BN as the normalization method by default, without reviewing its performance. In this paper, four normalization methods - BN, IN, LN and GN are compared and reviewed in details specifically for 2D bio-medical semantic segmentation. The result proved that GN out-performed the other three normalization methods - BN, IN and LN in 2D bio-medical semantic segmentation regarding both the accuracy and robustness. Unet is adopted as the basic DCNN structure. 37 RVs from both asymptomatic and Hypertrophic Cardiomyopathy (HCM) subjects and 20 aortas from asymptomatic subjects were used for the validation. The code and trained models will be available online.

##### Abstract (translated by Google)
2D生物医学语义分割对于手术机器人视觉非常重要。基于深度卷积神经网络（DCNN）的分割方法在准确性和自动化方面优于传统方法。训练DCNN的一个常见问题是内部协变量移位，其中卷积核被训练以适应输入特征的分布变化，因此训练速度和性能都降低。批量归一化（BN）是第一种用于解决内部协变量偏移的方法，并且被广泛使用。后来提出了实例规范化（IN）和层规范化（LN），并且使用的次数远低于BN。群规范化（GN）最近才提出，尚未应用于二维生物医学语义分割。大多数基于DCNN的生物医学语义分割默认采用BN作为归一化方法，而不考虑其性能。在本文中，四种标准化方法--BN，IN，LN和GN进行了详细的比较和审查，专门用于二维生物医学语义分割。结果证明GN在准确性和鲁棒性方面优于其他三种归一化方法--BN，IN和LN二维生物医学语义分割。 Unet被用作基本的DCNN结构。来自无症状和肥厚性心肌病（HCM）受试者的37个RV和来自无症状受试者的20个主动脉用于验证。代码和训练有素的模型将在线提供。

##### URL
[http://arxiv.org/abs/1809.03783](http://arxiv.org/abs/1809.03783)

##### PDF
[http://arxiv.org/pdf/1809.03783](http://arxiv.org/pdf/1809.03783)

