---
layout: post
title: "DOOBNet: Deep Object Occlusion Boundary Detection from an Image"
date: 2018-06-11 02:24:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Detection
author: Guoxia Wang, Xiaohui Liang, Frederick W. B. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object occlusion boundary detection is a fundamental and crucial research problem in computer vision. This is challenging to solve as encountering the extreme boundary/non-boundary class imbalance during training an object occlusion boundary detector. In this paper, we propose to address this class imbalance by up-weighting the loss contribution of false negative and false positive examples with our novel Attention Loss function. We also propose a unified end-to-end multi-task deep object occlusion boundary detection network (DOOBNet) by sharing convolutional features to simultaneously predict object boundary and occlusion orientation. DOOBNet adopts an encoder-decoder structure with skip connection in order to automatically learn multi-scale and multi-level features. We significantly surpass the state-of-the-art on the PIOD dataset (ODS F-score of .668) and the BSDS ownership dataset (ODS F-score of .555), as well as improving the detecting speed to as 0.037s per image.

##### Abstract (translated by Google)
对象遮挡边界检测是计算机视觉中的一个基础性和关键性研究问题。在训练物体遮挡边界检测器期间遇到极端边界/非边界类不平衡是解决这个问题的难题。在本文中，我们提出通过利用我们的新型注意力丢失函数来增加假阴性和假阳性例子的损失贡献来解决这类不平衡问题。我们还提出了一个统一的端到端多任务深度物体遮挡边界检测网络（DOOBNet），通过共享卷积特征来同时预测物体的边界和遮挡方向。 DOOBNet采用跳码连接的编码器 - 解码器结构，以自动学习多尺度和多层次的特性。我们在PIOD数据集（ODS F-score为0.668）和BSDS所有权数据集（ODS F-score为.555）方面显着超越了最新水平，并将检测速度提高到0.037s每张图片。

##### URL
[http://arxiv.org/abs/1806.03772](http://arxiv.org/abs/1806.03772)

##### PDF
[http://arxiv.org/pdf/1806.03772](http://arxiv.org/pdf/1806.03772)

