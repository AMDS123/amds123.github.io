---
layout: post
title: "Cystoid macular edema segmentation of Optical Coherence Tomography images using fully convolutional neural networks and fully connected CRFs"
date: 2017-09-15 17:33:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Fangliang Bai, Manuel J. Marques, Stuart J. Gibson
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a new method for cystoid macular edema (CME) segmentation in retinal Optical Coherence Tomography (OCT) images, using a fully convolutional neural network (FCN) and a fully connected conditional random fields (dense CRFs). As a first step, the framework trains the FCN model to extract features from retinal layers in OCT images, which exhibit CME, and then segments CME regions using the trained model. Thereafter, dense CRFs are used to refine the segmentation according to the edema appearance. We have trained and tested the framework with OCT images from 10 patients with diabetic macular edema (DME). Our experimental results show that fluid and concrete macular edema areas were segmented with good adherence to boundaries. A segmentation accuracy of $0.61\pm 0.21$ (Dice coefficient) was achieved, with respect to the ground truth, which compares favourably with the previous state-of-the-art that used a kernel regression based method ($0.51\pm 0.34$). Our approach is versatile and we believe it can be easily adapted to detect other macular defects.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法，使用完全卷积神经网络（FCN）和完全连接的条件随机场（密集的CRF）在视网膜光学相干断层扫描（OCT）图像中的囊样黄斑水肿（CME）分割。作为第一步，该框架训练FCN模型，以从展示CME的OCT图像中的视网膜层提取特征，然后使用训练的模型分割CME区域。此后，密集CRF被用来根据水肿外观来细化分割。我们用来自10位糖尿病性黄斑水肿（DME）患者的OCT图像训练和测试了框架。我们的实验结果表明，流体和混凝土黄斑水肿区域分割与良好的坚持边界。对于基本事实，分割准确度为0.61美元/分钟0.21美元（骰子系数），与使用基于核回归的方法（0.51美元/分钟0.34美元）的先前技术相比， 。我们的方法是多功能的，我们相信它可以很容易地适应检测其他黄斑缺陷。

##### URL
[https://arxiv.org/abs/1709.05324](https://arxiv.org/abs/1709.05324)

##### PDF
[https://arxiv.org/pdf/1709.05324](https://arxiv.org/pdf/1709.05324)

