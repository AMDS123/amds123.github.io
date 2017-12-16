---
layout: post
title: "EddyNet: A Deep Neural Network For Pixel-Wise Classification of Oceanic Eddies"
date: 2017-11-10 18:30:05
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning Detection
author: Redouane Lguensat, Miao Sun, Ronan Fablet, Evan Mason, Pierre Tandeo, Ge Chen
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents EddyNet, a deep learning based architecture for automated eddy detection and classification from Sea Surface Height (SSH) maps provided by the Copernicus Marine and Environment Monitoring Service (CMEMS). EddyNet is a U-Net like network that consists of a convolutional encoder-decoder followed by a pixel-wise classification layer. The output is a map with the same size of the input where pixels have the following labels \{'0': Non eddy, '1': anticyclonic eddy, '2': cyclonic eddy\}. We investigate the use of SELU activation function instead of the classical ReLU+BN and we use an overlap based loss function instead of the cross entropy loss. Keras Python code, the training datasets and EddyNet weights files are open-source and freely available on this https URL

##### Abstract (translated by Google)
这项工作提供了EddyNet，这是一个基于深度学习的架构，用于由哥白尼海洋和环境监测服务（CMEMS）提供的海面高度（SSH）地图进行自动涡流探测和分类。 EddyNet是一个类似U-Net的网络，由一个卷积编码器 - 解码器和一个逐像素分类层组成。输出是一个具有相同输入大小的地图，其中像素具有以下标签：\ {'0'：非漩涡，'1'：反气旋漩涡，'2'：旋风漩涡\}。我们研究SELU激活函数的使用，而不是经典的ReLU + BN，我们使用基于重叠的损失函数而不是交叉熵损失。 Keras Python代码，培训数据集和EddyNet权重文件都是开源的，并且可以在此https URL上免费获得

##### URL
[https://arxiv.org/abs/1711.03954](https://arxiv.org/abs/1711.03954)

##### PDF
[https://arxiv.org/pdf/1711.03954](https://arxiv.org/pdf/1711.03954)

