---
layout: post
title: "Learning Convolutional Neural Networks using Hybrid Orthogonal Projection and Estimation"
date: 2016-09-11 03:25:25
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Hengyue Pan, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have yielded the excellent performance in a variety of computer vision tasks, where CNNs typically adopt a similar structure consisting of convolution layers, pooling layers and fully connected layers. In this paper, we propose to apply a novel method, namely Hybrid Orthogonal Projection and Estimation (HOPE), to CNNs in order to introduce orthogonality into the CNN structure. The HOPE model can be viewed as a hybrid model to combine feature extraction using orthogonal linear projection with mixture models. It is an effective model to extract useful information from the original high-dimension feature vectors and meanwhile filter out irrelevant noises. In this work, we present three different ways to apply the HOPE models to CNNs, i.e., {\em HOPE-Input}, {\em single-HOPE-Block} and {\em multi-HOPE-Blocks}. For {\em HOPE-Input} CNNs, a HOPE layer is directly used right after the input to de-correlate high-dimension input feature vectors. Alternatively, in {\em single-HOPE-Block} and {\em multi-HOPE-Blocks} CNNs, we consider to use HOPE layers to replace one or more blocks in the CNNs, where one block may include several convolutional layers and one pooling layer. The experimental results on both Cifar-10 and Cifar-100 data sets have shown that the orthogonal constraints imposed by the HOPE layers can significantly improve the performance of CNNs in these image classification tasks (we have achieved one of the best performance when image augmentation has not been applied, and top 5 performance with image augmentation).

##### Abstract (translated by Google)
卷积神经网络（CNN）在各种计算机视觉任务中取得了优异的性能，其中CNN通常采用由卷积层，汇聚层和完全连通层组成的类似结构。在本文中，我们建议应用一种新的方法，即混合正交投影和估计（HOPE），以便在CNN结构中引入正交性。 HOPE模型可以被看作是一个混合模型，将使用正交线性投影的特征提取与混合模型相结合。从原有的高维特征向量中提取有用的信息，同时滤除不相关的噪声是一个有效的模型。在这项工作中，我们提出了三种不同的方法将HOPE模型应用到CNN，即{\ em HOPE-Input}，{\ em single-HOPE-Block}和{\ em multi-HOPE-Blocks}。对于{\ em HOPE-Input} CNN，直接在输入之后直接使用HOPE层来对高维输入特征向量进行去相关。或者，在{\ em single-HOPE-Block}和{\ em multi-HOPE-Blocks} CNN中，我们考虑使用HOPE层来替换CNN中的一个或多个块，其中一个块可以包括几个卷积层和一个合并图层。在Cifar-10和Cifar-100数据集上的实验结果表明，由HOPE层施加的正交约束可以显着提高CNN在这些图像分类任务中的性能（当图像增强已经实现了最好的性能之一时没有被应用，和图像增强的前5名表现）。

##### URL
[https://arxiv.org/abs/1606.05929](https://arxiv.org/abs/1606.05929)

##### PDF
[https://arxiv.org/pdf/1606.05929](https://arxiv.org/pdf/1606.05929)

