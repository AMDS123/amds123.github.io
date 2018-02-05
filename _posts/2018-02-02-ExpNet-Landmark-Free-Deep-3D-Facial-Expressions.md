---
layout: post
title: "ExpNet: Landmark-Free, Deep, 3D Facial Expressions"
date: 2018-02-02 02:42:44
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Detection Recognition
author: Feng-Ju Chang, Anh Tuan Tran, Tal Hassner, Iacopo Masi, Ram Nevatia, Gerard Medioni
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a deep learning based method for estimating 3D facial expression coefficients. Unlike previous work, our process does not relay on facial landmark detection methods as a proxy step. Recent methods have shown that a CNN can be trained to regress accurate and discriminative 3D morphable model (3DMM) representations, directly from image intensities. By foregoing facial landmark detection, these methods were able to estimate shapes for occluded faces appearing in unprecedented in-the-wild viewing conditions. We build on those methods by showing that facial expressions can also be estimated by a robust, deep, landmark-free approach. Our ExpNet CNN is applied directly to the intensities of a face image and regresses a 29D vector of 3D expression coefficients. We propose a unique method for collecting data to train this network, leveraging on the robustness of deep networks to training label noise. We further offer a novel means of evaluating the accuracy of estimated expression coefficients: by measuring how well they capture facial emotions on the CK+ and EmotiW-17 emotion recognition benchmarks. We show that our ExpNet produces expression coefficients which better discriminate between facial emotions than those obtained using state of the art, facial landmark detection techniques. Moreover, this advantage grows as image scales drop, demonstrating that our ExpNet is more robust to scale changes than landmark detection methods. Finally, at the same level of accuracy, our ExpNet is orders of magnitude faster than its alternatives.

##### Abstract (translated by Google)
我们描述了一个基于深度学习的方法来估计三维面部表情系数。与以前的工作不同，我们的过程不会将面部标志检测方法作为代理步骤进行中继。最近的方法已经表明可以训练CNN直接从图像强度中回归准确和有区别的3D形变模型（3DMM）表示。通过上述的面部标志检测，这些方法能够估计出现在前所未有的野外观察条件下的遮挡面的形状。我们以这些方法为基础，通过显示面部表情也可以通过一种强有力的，深刻的，具有里程碑意义的方法来估计。我们将ExpNet CNN直接应用于人脸图像的强度，并对三维表情系数的29D矢量进行回归。我们提出了一个独特的方法来收集数据来训练这个网络，利用深度网络的鲁棒性训练标签噪声。我们还提供了一种评估表达系数准确性的新方法：通过测量他们在CK +和EmotiW-17情感识别基准上捕捉面部表情的能力。我们表明，我们的ExpNet产生的表情系数比那些使用最先进的面部标志物检测技术获得的面部情绪更好地区分。而且，这种优势随着图像尺度的下降而增加，这表明我们的ExpNet比标志性检测方法更能适应比例变化。最后，在相同的准确度水平下，我们的ExpNet比其他选择快了几个数量级。

##### URL
[https://arxiv.org/abs/1802.00542](https://arxiv.org/abs/1802.00542)

##### PDF
[https://arxiv.org/pdf/1802.00542](https://arxiv.org/pdf/1802.00542)

