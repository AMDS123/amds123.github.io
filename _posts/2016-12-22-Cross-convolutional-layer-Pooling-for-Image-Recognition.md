---
layout: post
title: "Cross-convolutional-layer Pooling for Image Recognition"
date: 2016-12-22 04:43:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Image_Classification Classification Recognition
author: Lingqiao Liu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have shown that a Deep Convolutional Neural Network (DCNN) pretrained on a large image dataset can be used as a universal image descriptor, and that doing so leads to impressive performance for a variety of image classification tasks. Most of these studies adopt activations from a single DCNN layer, usually the fully-connected layer, as the image representation. In this paper, we proposed a novel way to extract image representations from two consecutive convolutional layers: one layer is utilized for local feature extraction and the other serves as guidance to pool the extracted features. By taking different viewpoints of convolutional layers, we further develop two schemes to realize this idea. The first one directly uses convolutional layers from a DCNN. The second one applies the pretrained CNN on densely sampled image regions and treats the fully-connected activations of each image region as convolutional feature activations. We then train another convolutional layer on top of that as the pooling-guidance convolutional layer. By applying our method to three popular visual classification tasks, we find our first scheme tends to perform better on the applications which need strong discrimination on subtle object patterns within small regions while the latter excels in the cases that require discrimination on category-level patterns. Overall, the proposed method achieves superior performance over existing ways of extracting image representations from a DCNN.

##### Abstract (translated by Google)
最近的研究表明，在大型图像数据集上预训练的深度卷积神经网络（DCNN）可以用作通用图像描述符，并且这样做可以为各种图像分类任务带来令人印象深刻的性能。这些研究大多采用单个DCNN层（通常是完全连接的层）的激活作为图像表示。在本文中，我们提出了一种从两个连续的卷积图层中提取图像表示的新方法：一个图层用于局部特征提取，另一个用作引导来提取所提取的特征。通过对卷积层的不同观点，我们进一步发展两种方案来实现这个思想。第一个直接使用DCNN的卷积层。第二种将预训练的CNN应用于密集采样的图像区域，并将每个图像区域的完全连接激活视为卷积特征激活。然后，我们训练另一个卷积层作为共引导卷积层。通过将我们的方法应用于三个流行的视觉分类任务，我们发现我们的第一个方案在小范围内需要强烈区分细微对象模式的应用方面表现更好，而后者在需要区分类别级别模式的情况下更胜一筹。总体而言，与现有的从DCNN中提取图像表示的方法相比，所提出的方法实现了优越的性能。

##### URL
[https://arxiv.org/abs/1510.00921](https://arxiv.org/abs/1510.00921)

##### PDF
[https://arxiv.org/pdf/1510.00921](https://arxiv.org/pdf/1510.00921)

