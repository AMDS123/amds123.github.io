---
layout: post
title: "Disentangling 3D Pose in A Dendritic CNN for Unconstrained 2D Face Alignment"
date: 2018-02-19 17:15:06
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification
author: Amit Kumar, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Heatmap regression has been used for landmark localization for quite a while now. Most of the methods use a very deep stack of bottleneck modules for heatmap classification stage, followed by heatmap regression to extract the keypoints. In this paper, we present a single dendritic CNN, termed as Pose Conditioned Dendritic Convolution Neural Network (PCD-CNN), where a classification network is followed by a second and modular classification network, trained in an end to end fashion to obtain accurate landmark points. Following a Bayesian formulation, we disentangle the 3D pose of a face image explicitly by conditioning the landmark estimation on pose, making it different from multi-tasking approaches. Extensive experimentation shows that conditioning on pose reduces the localization error by making it agnostic to face pose. The proposed model can be extended to yield variable number of landmark points and hence broadening its applicability to other datasets. Instead of increasing depth or width of the network, we train the CNN efficiently with Mask-Softmax Loss and hard sample mining to achieve upto $15\%$ reduction in error compared to state-of-the-art methods for extreme and medium pose face images from challenging datasets including AFLW, AFW, COFW and IBUG.

##### Abstract (translated by Google)
目前，热图回归已经用于地标定位。大多数方法使用非常深的一堆瓶颈模块进行热图分类，然后进行热图回归以提取关键点。在本文中，我们提出了一种叫做Pose Conditioned Dendritic Convolution Neural Network（PCD-CNN）的树突状CNN，其中分类网络后面是第二个模块化分类网络，以端到端的方式训练以获得准确的标志点。遵循贝叶斯公式，我们通过调整姿态的标志性估计来明确地解开人脸图像的3D姿态，使其不同于多任务方法。广泛的实验表明，姿态调节通过使姿势不可知而减少定位误差。所提出的模型可以扩展以产生可变数量的界标点，并因此扩大其对其他数据集的适用性。我们不用增加网络的深度或宽度，而是通过Mask-Softmax Loss和硬采样挖掘高效地训练CNN，与针对极端和中等姿势面的最先进方法相比，实现高达15％的误差减少图像来自具有挑战性的数据集，包括AFLW，AFW，COFW和IBUG。

##### URL
[http://arxiv.org/abs/1802.06713](http://arxiv.org/abs/1802.06713)

##### PDF
[http://arxiv.org/pdf/1802.06713](http://arxiv.org/pdf/1802.06713)

