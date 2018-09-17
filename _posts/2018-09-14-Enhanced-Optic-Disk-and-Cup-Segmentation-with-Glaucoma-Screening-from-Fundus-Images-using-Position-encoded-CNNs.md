---
layout: post
title: "Enhanced Optic Disk and Cup Segmentation with Glaucoma Screening from Fundus Images using Position encoded CNNs"
date: 2018-09-14 01:31:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Vismay Agrawal, Avinash Kori, Varghese Alex, Ganapathy Krishnamurthi
mathjax: true
---

* content
{:toc}

##### Abstract
In this manuscript, we present a robust method for glaucoma screening from fundus images using an ensemble of convolutional neural networks (CNNs). The pipeline comprises of first segmenting the optic disk and optic cup from the fundus image, then extracting a patch centered around the optic disk and subsequently feeding to the classification network to differentiate the image as diseased or healthy. In the segmentation network, apart from the image, we make use of spatial co-ordinate (X \&amp; Y) space so as to learn the structure of interest better. The classification network is composed of a DenseNet201 and a ResNet18 which were pre-trained on a large cohort of natural images. On the REFUGE validation data (n=400), the segmentation network achieved a dice score of 0.88 and 0.64 for optic disc and optic cup respectively. For the tasking differentiating images affected with glaucoma from healthy images, the area under the ROC curve was observed to be 0.85.

##### Abstract (translated by Google)
在这篇手稿中，我们提出了一种使用卷积神经网络（CNN）集合从眼底图像中筛查青光眼的有效方法。该管道包括首先从眼底图像分割视盘和视杯，然后提取以视盘为中心的贴片，随后馈送到分类网络以将图像区分为患病或健康。在分割网络中，除了图像之外，我们利用空间坐标（X \＆amp; Y）空间以更好地学习感兴趣的结构。分类网络由DenseNet201和ResNet18组成，这些网络在大量自然图像上进行了预训练。在REFUGE验证数据（n = 400）上，分割网络分别实现了视盘和视杯的骰子评分0.88和0.64。对于来自健康图像的患有青光眼的任务区分图像，观察到ROC曲线下面积为0.85。

##### URL
[http://arxiv.org/abs/1809.05216](http://arxiv.org/abs/1809.05216)

##### PDF
[http://arxiv.org/pdf/1809.05216](http://arxiv.org/pdf/1809.05216)

