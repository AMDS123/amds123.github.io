---
layout: post
title: "A Counter-Forensic Method for CNN-Based Camera Model Identification"
date: 2018-05-06 01:32:08
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Object_Detection CNN Deep_Learning Detection
author: David G&#xfc;era, Yu Wang, Luca Bondi, Paolo Bestagini, Stefano Tubaro, Edward J. Delp
mathjax: true
---

* content
{:toc}

##### Abstract
An increasing number of digital images are being shared and accessed through websites, media, and social applications. Many of these images have been modified and are not authentic. Recent advances in the use of deep convolutional neural networks (CNNs) have facilitated the task of analyzing the veracity and authenticity of largely distributed image datasets. We examine in this paper the problem of identifying the camera model or type that was used to take an image and that can be spoofed. Due to the linear nature of CNNs and the high-dimensionality of images, neural networks are vulnerable to attacks with adversarial examples. These examples are imperceptibly different from correctly classified images but are misclassified with high confidence by CNNs. In this paper, we describe a counter-forensic method capable of subtly altering images to change their estimated camera model when they are analyzed by any CNN-based camera model detector. Our method can use both the Fast Gradient Sign Method (FGSM) or the Jacobian-based Saliency Map Attack (JSMA) to craft these adversarial images and does not require direct access to the CNN. Our results show that even advanced deep learning architectures trained to analyze images and obtain camera model information are still vulnerable to our proposed method.

##### Abstract (translated by Google)
越来越多的数字图像正在通过网站，媒体和社交应用进行共享和访问。这些图像中的许多图像已被修改并且不可信。最近在使用深度卷积神经网络（CNN）方面的进展促进了分析大量分布图像数据集的准确性和真实性的任务。我们在本文中研究识别用于拍摄图像并可能被欺骗的相机型号或类型的问题。由于CNN的线性特性和图像的高维性，神经网络容易受到敌对攻击的攻击。这些例子与正确分类的图像有着不可察觉的不同，但被CNN高度置信地错误分类。在本文中，我们描述了一种能够巧妙地改变图像以改变其估计的相机模型（当它们被任何基于CNN的相机模型检测器分析时）的反取证方法。我们的方法既可以使用快速梯度符号法（FGSM），也可以使用基于雅可比矩阵的显着图攻击法（JSMA）制作这些对抗图像，并且不需要直接访问CNN。我们的研究结果表明，即使先进的深度学习体系结构经过训练分析图像和获取相机模型信息仍然容易受到我们提出的方法。

##### URL
[http://arxiv.org/abs/1805.02131](http://arxiv.org/abs/1805.02131)

##### PDF
[http://arxiv.org/pdf/1805.02131](http://arxiv.org/pdf/1805.02131)

