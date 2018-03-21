---
layout: post
title: "Land cover mapping at very high resolution with rotation equivariant CNNs: towards small yet accurate models"
date: 2018-03-16 14:48:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Diego Marcos, Michele Volpi, Benjamin Kellenberger, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
In remote sensing images, the absolute orientation of objects is arbitrary. Depending on an object's orientation and on a sensor's flight path, objects of the same semantic class can be observed in different orientations in the same image. Equivariance to rotation, in this context understood as responding with a rotated semantic label map when subject to a rotation of the input image, is therefore a very desirable feature, in particular for high capacity models, such as Convolutional Neural Networks (CNNs). If rotation equivariance is encoded in the network, the model is confronted with a simpler task and does not need to learn specific (and redundant) weights to address rotated versions of the same object class. In this work we propose a CNN architecture called Rotation Equivariant Vector Field Network (RotEqNet) to encode rotation equivariance in the network itself. By using rotating convolutions as building blocks and passing only the the values corresponding to the maximally activating orientation throughout the network in the form of orientation encoding vector fields, RotEqNet treats rotated versions of the same object with the same filter bank and therefore achieves state-of-the-art performances even when using very small architectures trained from scratch. We test RotEqNet in two challenging sub-decimeter resolution semantic labeling problems, and show that we can perform better than a standard CNN while requiring one order of magnitude less parameters.

##### Abstract (translated by Google)
在遥感图像中，物体的绝对方向是任意的。根据对象的方向和传感器的飞行路径，可以在同一图像中以不同的方向观察同一语义类别的对象。因此，在这种情况下，旋转的等效性被理解为当受到输入图像的旋转时用旋转的语义标签映射进行响应，因此是非常理想的特征，特别是对于诸如卷积神经网络（CNN）的高容量模型。如果旋转等变性在网络中编码，那么该模型面临更简单的任务，并且不需要学习特定（和冗余）权重来解决相同对象类别的旋转版本。在这项工作中，我们提出了一种称为旋转等变矢量场网络（RotEqNet）的CNN架构来编码网络自身的旋转等距变量。通过使用旋转卷积作为构件，并以方向编码矢量场的形式仅传递整个网络中与最大激活方向相对应的值，RotEqNet将相同对象的旋转版本视为同一个滤波器组，从而实现状态即使在使用从头开始训练的非常小的体系结构时也能表现出最先进的性能我们在两个具有挑战性的亚分辨率语义标注问题中测试RotEqNet，并表明我们可以比标准CNN执行得更好，同时要求的参数少一个数量级。

##### URL
[https://arxiv.org/abs/1803.06253](https://arxiv.org/abs/1803.06253)

##### PDF
[https://arxiv.org/pdf/1803.06253](https://arxiv.org/pdf/1803.06253)

