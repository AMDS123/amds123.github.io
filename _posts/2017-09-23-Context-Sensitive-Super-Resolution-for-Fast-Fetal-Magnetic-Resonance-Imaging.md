---
layout: post
title: "Context-Sensitive Super-Resolution for Fast Fetal Magnetic Resonance Imaging"
date: 2017-09-23 10:21:06
categories: arXiv_CV
tags: arXiv_CV Super_Resolution GAN CNN
author: Steven McDonagh, Benjamin Hou, Konstantinos Kamnitsas, Ozan Oktay, Amir Alansary, Mary Rutherford, Jo V. Hajnal, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
3D Magnetic Resonance Imaging (MRI) is often a trade-off between fast but low-resolution image acquisition and highly detailed but slow image acquisition. Fast imaging is required for targets that move to avoid motion artefacts. This is in particular difficult for fetal MRI. Spatially independent upsampling techniques, which are the state-of-the-art to address this problem, are error prone and disregard contextual information. In this paper we propose a context-sensitive upsampling method based on a residual convolutional neural network model that learns organ specific appearance and adopts semantically to input data allowing for the generation of high resolution images with sharp edges and fine scale detail. By making contextual decisions about appearance and shape, present in different parts of an image, we gain a maximum of structural detail at a similar contrast as provided by high-resolution data. We experiment on $145$ fetal scans and show that our approach yields an increased PSNR of $1.25$ $dB$ when applied to under-sampled fetal data \emph{cf.} baseline upsampling. Furthermore, our method yields an increased PSNR of $1.73$ $dB$ when utilizing under-sampled fetal data to perform brain volume reconstruction on motion corrupted captured data.

##### Abstract (translated by Google)
3D磁共振成像（MRI）通常是快速但低分辨率的图像采集和高度详细但低速的图像采集之间的折衷。移动的目标需要快速成像以避免运动伪影。这对于胎儿MRI尤其困难。空间独立的上采样技术是解决这个问题的最先进技术，容易出错并忽视上下文信息。在本文中，我们提出了基于残留卷积神经网络模型的上下文敏感的上采样方法，该模型学习器官特定的外观，并且在语义上采用输入数据，允许产生具有尖锐边缘和细节细节的高分辨率图像。通过对外观和形状进行上下文决策，呈现在图像的不同部分，我们获得了与高分辨率数据相似的对比度下的最大结构细节。我们对145美元的胎儿扫描进行了实验，结果表明当应用于欠采样的胎儿数据基线上采样时，我们的方法得到的增加的PSNR为$ 1.25 $ $ dB $。此外，当利用欠采样的胎儿数据对运动损坏的捕获数据进行大脑重建时，我们的方法产生的增​​加的PSNR为$ 1.73 $ $ dB $。

##### URL
[https://arxiv.org/abs/1703.00035](https://arxiv.org/abs/1703.00035)

##### PDF
[https://arxiv.org/pdf/1703.00035](https://arxiv.org/pdf/1703.00035)

