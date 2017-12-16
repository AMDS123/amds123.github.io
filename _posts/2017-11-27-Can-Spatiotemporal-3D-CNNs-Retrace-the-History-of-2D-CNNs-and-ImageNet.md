---
layout: post
title: "Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?"
date: 2017-11-27 08:29:06
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Kensho Hara, Hirokatsu Kataoka, Yutaka Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
The purpose of this study is to determine whether current video datasets have sufficient data for training very deep convolutional neural networks (CNNs) with spatio-temporal three-dimensional (3D) kernels. Recently, the performance levels of 3D CNNs in the field of action recognition have improved significantly. However, to date, conventional research has only explored relatively shallow3Darchitectures. We examine the architectures of various 3D CNNs from relatively shallow to very deep ones on current video datasets. Based on the results of those experiments, the following conclusions could be obtained: (i) ResNet-18 training resulted in significant overfitting for UCF-101, HMDB-51, and ActivityNet but not for Kinetics. (ii) The Kinetics dataset has sufficient data for training of deep 3D CNNs, and enables training of up to 152 ResNets layers, interestingly similar to 2D ResNets on ImageNet. (iii) Kinetics pretrained simple 3D architectures outperforms complex2D architectures, and the pretrained ResNeXt-101 achieved 94.5% and 70.2% on UCF-101 and HMDB-51, respectively. The use of 2D CNNs trained on ImageNet has produced significant progress in various tasks in image. We believe that using deep 3D CNNs together with Kinetics will retrace the successful history of 2D CNNs and ImageNet, and stimulate advances in computer vision for videos. The codes and pretrained models used in this study are publicly available.

##### Abstract (translated by Google)
本研究的目的是确定当前视频数据集是否具有足够的数据来训练具有时空三维（3D）内核的非常深的卷积神经网络（CNN）。近日，3D CNN在行动识别领域的表现水平显着提升。但是，迄今为止，传统的研究只是探索了相对较浅的三维建筑。我们在当前的视频数据集上研究各种3D CNN的结构，从相对较浅到较深的结构。根据这些实验的结果，可以得出以下结论：（i）ResNet-18训练导致对UCF-101，HMDB-51和ActivityNet显着的过度拟合，但是对于动力学而言不是。 （ii）动力学数据集具有足够的深度3D CNN训练数据，并且可以训练多达152个ResNets层，有趣的是类似于ImageNet上的2D ResNets。 （iii）动力学预训简单的三维结构优于复杂的二维结构，预研ResNeXt-101分别在UCF-101和HMDB-51上分别达到94.5％和70.2％。在ImageNet上使用2D CNN已经在图像的各种任务中取得了重大进展。我们相信，将深度3D CNN与动力学一起使用，将回溯2D CNN和ImageNet的成功历史，并刺激视频计算机视觉领域的进步。本研究中使用的代码和预训练模型是公开可用的。

##### URL
[https://arxiv.org/abs/1711.09577](https://arxiv.org/abs/1711.09577)

##### PDF
[https://arxiv.org/pdf/1711.09577](https://arxiv.org/pdf/1711.09577)

