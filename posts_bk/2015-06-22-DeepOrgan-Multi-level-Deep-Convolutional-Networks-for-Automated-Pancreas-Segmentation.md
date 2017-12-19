---
layout: post
title: "DeepOrgan: Multi-level Deep Convolutional Networks for Automated Pancreas Segmentation"
date: 2015-06-22 02:56:42
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Prediction
author: Holger R. Roth, Le Lu, Amal Farag, Hoo-Chang Shin, Jiamin Liu, Evrim Turkbey, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic organ segmentation is an important yet challenging problem for medical image analysis. The pancreas is an abdominal organ with very high anatomical variability. This inhibits previous segmentation methods from achieving high accuracies, especially compared to other organs such as the liver, heart or kidneys. In this paper, we present a probabilistic bottom-up approach for pancreas segmentation in abdominal computed tomography (CT) scans, using multi-level deep convolutional networks (ConvNets). We propose and evaluate several variations of deep ConvNets in the context of hierarchical, coarse-to-fine classification on image patches and regions, i.e. superpixels. We first present a dense labeling of local image patches via $P{-}\mathrm{ConvNet}$ and nearest neighbor fusion. Then we describe a regional ConvNet ($R_1{-}\mathrm{ConvNet}$) that samples a set of bounding boxes around each image superpixel at different scales of contexts in a "zoom-out" fashion. Our ConvNets learn to assign class probabilities for each superpixel region of being pancreas. Last, we study a stacked $R_2{-}\mathrm{ConvNet}$ leveraging the joint space of CT intensities and the $P{-}\mathrm{ConvNet}$ dense probability maps. Both 3D Gaussian smoothing and 2D conditional random fields are exploited as structured predictions for post-processing. We evaluate on CT images of 82 patients in 4-fold cross-validation. We achieve a Dice Similarity Coefficient of 83.6$\pm$6.3% in training and 71.8$\pm$10.7% in testing.

##### Abstract (translated by Google)
自动器官分割对医学图像分析来说是一个重要而又具有挑战性的问胰腺是具有非常高的解剖变异性的腹部器官。这抑制了先前的分割方法实现高精度，特别是与其他器官如肝脏，心脏或肾脏相比。在本文中，我们提出了一个概率自底向上的方法胰腺分割在腹部计算机断层扫描（CT）扫描，使用多层次的深度卷积网络（ConvNets）。我们提出和评估深层次的几个变化，在图像块和区域，即超级像素的分级，从粗到细的分类的上下文。我们首先通过$ P { - } \ mathrm {ConvNet} $和最近的邻居融合给出一个局部图像块的稠密标记。然后，我们描述一个区域ConvNet（$ R_1 { - } \ mathrm {ConvNet} $），以“缩小”的方式在不同的上下文范围内对每个图像超像素周围的一组边界框进行采样。我们的学习者学会为每个胰腺超像素区域分配类别概率。最后，我们研究了利用CT强度和$ P { - } \ mathrm {ConvNet} $密集概率图的联合空间的叠加$ R_2 { - } \ mathrm {ConvNet} $。 3D高斯平滑和2D条件随机场都被用作后处理的结构化预测。我们对82例患者的CT图像进行4倍交叉验证评估。我们在训练中获得了83.6 $ \ pm $ 6.3％的骰子相似系数，在测试中获得了71.8 $ \ pm $ 10.7％的骰子相似系数。

##### URL
[https://arxiv.org/abs/1506.06448](https://arxiv.org/abs/1506.06448)

##### PDF
[https://arxiv.org/pdf/1506.06448](https://arxiv.org/pdf/1506.06448)

