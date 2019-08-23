---
layout: post
title: "U-Net Training with Instance-Layer Normalization"
date: 2019-08-21 11:24:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Xiao-Yun Zhou, Qing-Biao Li, Mali Shen, Peichao Li, Zhao-Yang Wang, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Normalization layers are essential in a Deep Convolutional Neural Network (DCNN). Various normalization methods have been proposed. The statistics used to normalize the feature maps can be computed at batch, channel, or instance level. However, in most of existing methods, the normalization for each layer is fixed. Batch-Instance Normalization (BIN) is one of the first proposed methods that combines two different normalization methods and achieve diverse normalization for different layers. However, two potential issues exist in BIN: first, the Clip function is not differentiable at input values of 0 and 1; second, the combined feature map is not with a normalized distribution which is harmful for signal propagation in DCNN. In this paper, an Instance-Layer Normalization (ILN) layer is proposed by using the Sigmoid function for the feature map combination, and cascading group normalization. The performance of ILN is validated on image segmentation of the Right Ventricle (RV) and Left Ventricle (LV) using U-Net as the network architecture. The results show that the proposed ILN outperforms previous traditional and popular normalization methods with noticeable accuracy improvements for most validations, supporting the effectiveness of the proposed ILN.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08466](https://arxiv.org/abs/1908.08466)

##### PDF
[https://arxiv.org/pdf/1908.08466](https://arxiv.org/pdf/1908.08466)

