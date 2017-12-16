---
layout: post
title: "Computationally Efficient Target Classification in Multispectral Image Data with Deep Neural Networks"
date: 2016-11-09 23:13:18
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Lukas Cavigelli, Dominic Bernath, Michele Magno, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting and classifying targets in video streams from surveillance cameras is a cumbersome, error-prone and expensive task. Often, the incurred costs are prohibitive for real-time monitoring. This leads to data being stored locally or transmitted to a central storage site for post-incident examination. The required communication links and archiving of the video data are still expensive and this setup excludes preemptive actions to respond to imminent threats. An effective way to overcome these limitations is to build a smart camera that transmits alerts when relevant video sequences are detected. Deep neural networks (DNNs) have come to outperform humans in visual classifications tasks. The concept of DNNs and Convolutional Networks (ConvNets) can easily be extended to make use of higher-dimensional input data such as multispectral data. We explore this opportunity in terms of achievable accuracy and required computational effort. To analyze the precision of DNNs for scene labeling in an urban surveillance scenario we have created a dataset with 8 classes obtained in a field experiment. We combine an RGB camera with a 25-channel VIS-NIR snapshot sensor to assess the potential of multispectral image data for target classification. We evaluate several new DNNs, showing that the spectral information fused together with the RGB frames can be used to improve the accuracy of the system or to achieve similar accuracy with a 3x smaller computation effort. We achieve a very high per-pixel accuracy of 99.1%. Even for scarcely occurring, but particularly interesting classes, such as cars, 75% of the pixels are labeled correctly with errors occurring only around the border of the objects. This high accuracy was obtained with a training set of only 30 labeled images, paving the way for fast adaptation to various application scenarios.

##### Abstract (translated by Google)
在监视摄像机的视频流中检测和分类目标是一项麻烦，容易出错和昂贵的任务。通常，所发生的成本对于实时监控而言是不可接受的。这导致数据被存储在本地或传输到中央存储站点进行事后检查。视频数据所需的通信链接和归档仍然很昂贵，这种设置排除了抢先行动来应对迫在眉睫的威胁。克服这些限制的有效方法是构建智能相机，在相关视频序列被检测到时发送警报。深度神经网络（DNNs）在视觉分类任务中已经超越了人类。 DNN和卷积网络（ConvNets）的概念可以很容易地扩展，以利用更高维度的输入数据，如多光谱数据。我们在可实现的精度和所需的计算工作方面探索这个机会。为了在城市监控场景中分析场景标注DNNs的精度，我们创建了一个在现场实验中获得的8个类别的数据集。我们将RGB相机与25通道VIS-NIR快照传感器相结合，以评估多光谱图像数据用于目标分类的潜力。我们评估了几个新的DNNs，表明与RGB帧融合在一起的光谱信息可以用来提高系​​统的精确度，或者用3倍的计算量实现类似的精度。我们实现了99.1％的非常高的每像素精度。即使几乎没有发生，但特别有趣的类，如汽车，75％的像素被正确标记，错误只发生在对象的边界。这个高精度的训练集只有30个标记的图像，为快速适应各种应用场景铺平了道路。

##### URL
[https://arxiv.org/abs/1611.03130](https://arxiv.org/abs/1611.03130)

##### PDF
[https://arxiv.org/pdf/1611.03130](https://arxiv.org/pdf/1611.03130)

