---
layout: post
title: "Comparison of the Deep-Learning-Based Automated Segmentation Methods for the Head Sectioned Images of the Virtual Korean Human Project"
date: 2017-03-15 06:49:01
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Prediction Quantitative
author: Mohammad Eshghi, Holger R. Roth, Masahiro Oda, Min Suk Chung, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an end-to-end pixelwise fully automated segmentation of the head sectioned images of the Visible Korean Human (VKH) project based on Deep Convolutional Neural Networks (DCNNs). By converting classification networks into Fully Convolutional Networks (FCNs), a coarse prediction map, with smaller size than the original input image, can be created for segmentation purposes. To refine this map and to obtain a dense pixel-wise output, standard FCNs use deconvolution layers to upsample the coarse map. However, upsampling based on deconvolution increases the number of network parameters and causes loss of detail because of interpolation. On the other hand, dilated convolution is a new technique introduced recently that attempts to capture multi-scale contextual information without increasing the network parameters while keeping the resolution of the prediction maps high. We used both a standard FCN and a dilated convolution based FCN for semantic segmentation of the head sectioned images of the VKH dataset. Quantitative results showed approximately 20% improvement in the segmentation accuracy when using FCNs with dilated convolutions.

##### Abstract (translated by Google)
本文提出了一种基于深度卷积神经网络（DCNN）的可视化韩国人（VKH）项目的头部切片图像端到端像素全自动分割。通过将分类网络转换为完全卷积网络（FCN），可以创建具有比原始输入图像更小尺寸的粗略预测图用于分割目的。为了细化这张地图并获得密集的按像素输出，标准FCN使用解卷积层对粗略地图进行上采样。但是，基于反卷积的上采样增加了网络参数的数量，并且由于插值导致细节的损失。另一方面，扩张卷积是最近引入的一种新技术，试图在不增加网络参数的情况下捕获多尺度上下文信息，同时保持预测图的分辨率高。我们使用标准的FCN和基于膨胀的卷积的FCN来对VKH数据集的头部切片图像进行语义分割。定量结果显示，当使用具有扩张卷积的FCN时，分割准确度大约提高了20％。

##### URL
[https://arxiv.org/abs/1703.04967](https://arxiv.org/abs/1703.04967)

##### PDF
[https://arxiv.org/pdf/1703.04967](https://arxiv.org/pdf/1703.04967)

