---
layout: post
title: "Temporal HeartNet: Towards Human-Level Automatic Analysis of Fetal Cardiac Screening Video"
date: 2017-07-03 17:31:16
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Weilin Huang, Christopher P. Bridge, J. Alison Noble, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
We present an automatic method to describe clinically useful information about scanning, and to guide image interpretation in ultrasound (US) videos of the fetal heart. Our method is able to jointly predict the visibility, viewing plane, location and orientation of the fetal heart at the frame level. The contributions of the paper are three-fold: (i) a convolutional neural network architecture is developed for a multi-task prediction, which is computed by sliding a 3x3 window spatially through convolutional maps. (ii) an anchor mechanism and Intersection over Union (IoU) loss are applied for improving localization accuracy. (iii) a recurrent architecture is designed to recursively compute regional convolutional features temporally over sequential frames, allowing each prediction to be conditioned on the whole video. This results in a spatial-temporal model that precisely describes detailed heart parameters in challenging US videos. We report results on a real-world clinical dataset, where our method achieves performance on par with expert annotations.

##### Abstract (translated by Google)
我们提出一种自动方法来描述临床上有用的扫描信息，并引导胎儿心脏的超声（美国）视频图像解释。我们的方法能够联合预测胎儿心脏在框架水平的能见度，观察平面，位置和方向。本文的贡献有三个方面：（1）卷积神经网络架构开发的多任务预测，这是通过滑动3×3窗口空间通过卷积地图计算。 （ii）锚定机制和联合交叉（IoU）损失被应用于提高定位准确性。 （iii）经常性架构被设计为在递归帧上递归计算区域卷积特征，允许每个预测在整个视频上被调节。这导致了一个精确描述具有挑战性的美国视频中的详细心脏参数的时空模型。我们在真实世界的临床数据集上报告结果，我们的方法可以达到与专家注释一致的性能。

##### URL
[https://arxiv.org/abs/1707.00665](https://arxiv.org/abs/1707.00665)

##### PDF
[https://arxiv.org/pdf/1707.00665](https://arxiv.org/pdf/1707.00665)

