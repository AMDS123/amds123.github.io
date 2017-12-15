---
layout: post
title: "RotationNet: Joint Object Categorization and Pose Estimation Using Multiviews from Unsupervised Viewpoints"
date: 2017-11-30 10:17:17
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference Classification
author: Asako Kanezaki, Yasuyuki Matsushita, Yoshifumi Nishida
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Convolutional Neural Network (CNN)-based model "RotationNet," which takes multi-view images of an object as input and jointly estimates its pose and object category. Unlike previous approaches that use known viewpoint labels for training, our method treats the viewpoint labels as latent variables, which are learned in an unsupervised manner during the training using an unaligned object dataset. RotationNet is designed to use only a partial set of multi-view images for inference, and this property makes it useful in practical scenarios where only partial views are available. Moreover, our pose alignment strategy enables one to obtain view-specific feature representations shared across classes, which is important to maintain high accuracy in both object categorization and pose estimation. Effectiveness of RotationNet is demonstrated by its superior performance to the state-of-the-art methods of 3D object classification on 10- and 40-class ModelNet datasets. We also show that RotationNet, even trained without known poses, achieves the state-of-the-art performance on an object pose estimation dataset. The code is available on this https URL

##### Abstract (translated by Google)
我们提出了一个基于卷积神经网络（CNN）的模型“RotationNet”，它将一个物体的多视点图像作为输入，共同估计其姿态和物体类别。与以前使用已知视点标签进行训练的方法不同，我们的方法将视点标签视为潜在变量，这些潜在变量在训练期间使用未对齐的对象数据集以无监督的方式学习。 RotationNet被设计为仅使用一部分多视图图像进行推断，并且该属性使得在仅有部分视图可用的实际场景中是有用的。此外，我们的姿势对齐策略使得能够获得跨类共享的特定于视点的特征表示，这对于在对象分类和姿态估计中保持高精度是重要的。 RotationNet的有效性表现在其优异的性能，以及10级和40级ModelNet数据集上最先进的三维物体分类方法。我们还表明，RotationNet，即使训练没有已知的姿势，实现了对象姿态估计数据集的最先进的性能。该代码可在此https网址上找到

##### URL
[https://arxiv.org/abs/1603.06208](https://arxiv.org/abs/1603.06208)

##### PDF
[https://arxiv.org/pdf/1603.06208](https://arxiv.org/pdf/1603.06208)

