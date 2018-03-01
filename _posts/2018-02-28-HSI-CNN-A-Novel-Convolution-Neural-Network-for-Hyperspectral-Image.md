---
layout: post
title: "HSI-CNN: A Novel Convolution Neural Network for Hyperspectral Image"
date: 2018-02-28 15:31:20
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: Yanan Luo, Jie Zou, Chengfei Yao, Tao Li, Gang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
With the development of deep learning, the performance of hyperspectral image (HSI) classification has been greatly improved in recent years. The shortage of training samples has become a bottleneck for further improvement of performance. In this paper, we propose a novel convolutional neural network framework for the characteristics of hyperspectral image data, called HSI-CNN. Firstly, the spectral-spatial feature is extracted from a target pixel and its neighbors. Then, a number of one-dimensional feature maps, obtained by convolution operation on spectral-spatial features, are stacked into a two-dimensional matrix. Finally, the two-dimensional matrix considered as an image is fed into standard CNN. This is why we call it HSI-CNN. In addition, we also implements two depth network classification models, called HSI-CNN+XGBoost and HSI-CapsNet, in order to compare the performance of our framework. Experiments show that the performance of hyperspectral image classification is improved efficiently with HSI-CNN framework. We evaluate the model's performance using four popular HSI datasets, which are the Kennedy Space Center (KSC), Indian Pines (IP), Pavia University scene (PU) and Salinas scene (SA). As far as we concerned, HSI-CNN has got the state-of-art accuracy among all methods we have known on these datasets of 99.28%, 99.09%, 99.42%, 98.95% separately.

##### Abstract (translated by Google)
随着深度学习的发展，近年来高光谱图像（HSI）分类的性能有了很大提高。培训样本的短缺已成为进一步提高绩效的瓶颈。在本文中，我们提出了一种新的高光谱图像数据特征的卷积神经网络框架，称为HSI-CNN。首先，从目标像素及其邻居中提取光谱空间特征。然后，通过对光谱空间特征进行卷积运算获得的许多一维特征映射被堆叠成二维矩阵。最后，被认为是图像的二维矩阵被输入到标准的CNN中。这就是我们称之为HSI-CNN的原因。此外，我们还实施了两个深度网络分类模型，称为HSI-CNN + XGBoost和HSI-CapsNet，以便比较我们框架的性能。实验表明，HSI-CNN框架能有效地提高高光谱图像分类的性能。我们使用四个流行的HSI数据集（肯尼迪航天中心（KSC），印度松树（IP），帕维亚大学景观（PU）和萨利纳斯景观（SA））来评估模型的性能。就我们而言，HSI-CNN在这些数据集中已知的所有方法中分别获得了99.28％，99.09％，99.42％，98.95％的最新准确度。

##### URL
[http://arxiv.org/abs/1802.10478](http://arxiv.org/abs/1802.10478)

##### PDF
[http://arxiv.org/pdf/1802.10478](http://arxiv.org/pdf/1802.10478)

