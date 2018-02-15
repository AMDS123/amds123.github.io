---
layout: post
title: "Satellite Image Forgery Detection and Localization Using GAN and One-Class Classifier"
date: 2018-02-13 22:28:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Sri Kalyan Yarlagadda, David G&#xfc;era, Paolo Bestagini, Fengqing Maggie Zhu, Stefano Tubaro, Edward J. Delp
mathjax: true
---

* content
{:toc}

##### Abstract
Current satellite imaging technology enables shooting high-resolution pictures of the ground. As any other kind of digital images, overhead pictures can also be easily forged. However, common image forensic techniques are often developed for consumer camera images, which strongly differ in their nature from satellite ones (e.g., compression schemes, post-processing, sensors, etc.). Therefore, many accurate state-of-the-art forensic algorithms are bound to fail if blindly applied to overhead image analysis. Development of novel forensic tools for satellite images is paramount to assess their authenticity and integrity. In this paper, we propose an algorithm for satellite image forgery detection and localization. Specifically, we consider the scenario in which pixels within a region of a satellite image are replaced to add or remove an object from the scene. Our algorithm works under the assumption that no forged images are available for training. Using a generative adversarial network (GAN), we learn a feature representation of pristine satellite images. A one-class support vector machine (SVM) is trained on these features to determine their distribution. Finally, image forgeries are detected as anomalies. The proposed algorithm is validated against different kinds of satellite images containing forgeries of different size and shape.

##### Abstract (translated by Google)
目前的卫星成像技术能够拍摄高分辨率的地面图像。像任何其他类型的数字图像一样，头顶图片也可以很容易伪造。然而，常见的图像取证技术通常是针对消费者相机图像开发的，这些图像的性质与卫星图像的性质（例如，压缩方案，后处理，传感器等）明显不同。因此，如果盲目应用于开销图像分析，许多精确的最先进的取证算法必然会失败。开发卫星图像新型取证工具对评估其真实性和完整性至关重要。在本文中，我们提出了一种卫星图像伪造检测和定位算法。具体来说，我们考虑将卫星图像的区域内的像素替换为从场景中添加或移除物体的场景。我们的算法在没有伪造图像可用于训练的假设下工作。使用生成对抗网络（GAN），我们学习了原始卫星图像的特征表示。对这些特征进行一类支持向量机（SVM）的训练以确定它们的分布。最后，图像伪造被检测为异常。该算法针对不同大小和形状伪造的不同卫星图像进行验证。

##### URL
[http://arxiv.org/abs/1802.04881](http://arxiv.org/abs/1802.04881)

##### PDF
[http://arxiv.org/pdf/1802.04881](http://arxiv.org/pdf/1802.04881)

