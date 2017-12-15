---
layout: post
title: "V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation"
date: 2016-06-15 14:55:09
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Fausto Milletari, Nassir Navab, Seyed-Ahmad Ahmadi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have been recently employed to solve problems from both the computer vision and medical image analysis fields. Despite their popularity, most approaches are only able to process 2D images while most medical data used in clinical practice consists of 3D volumes. In this work we propose an approach to 3D image segmentation based on a volumetric, fully convolutional, neural network. Our CNN is trained end-to-end on MRI volumes depicting prostate, and learns to predict segmentation for the whole volume at once. We introduce a novel objective function, that we optimise during training, based on Dice coefficient. In this way we can deal with situations where there is a strong imbalance between the number of foreground and background voxels. To cope with the limited number of annotated volumes available for training, we augment the data applying random non-linear transformations and histogram matching. We show in our experimental evaluation that our approach achieves good performances on challenging test data while requiring only a fraction of the processing time needed by other previous methods.

##### Abstract (translated by Google)
卷积神经网络（CNN）近来被用来解决计算机视觉和医学图像分析领域的问题。尽管它们很受欢迎，但大多数方法只能处理2D图像，而临床实践中使用的大多数医学数据是由3D体积组成的。在这项工作中，我们提出了一种基于容积完全卷积神经网络的三维图像分割方法。我们的CNN在描绘前列腺的MRI体积上进行了端对端的培训，并学习一次预测整个体积的分割。我们引入了一个新的目标函数，即在训练期间根据Dice系数进行优化。通过这种方式，我们可以处理前景和背景体素之间强烈不平衡的情况。为了应对可用于训练的有限数量的注释卷，我们使用随机非线性变换和直方图匹配来增加数据。我们在我们的实验评估中表明，我们的方法在挑战性测试数据方面实现了良好的性能，而只需要以前其他方法所需的处理时间的一小部分。

##### URL
[https://arxiv.org/abs/1606.04797](https://arxiv.org/abs/1606.04797)

##### PDF
[https://arxiv.org/pdf/1606.04797](https://arxiv.org/pdf/1606.04797)

