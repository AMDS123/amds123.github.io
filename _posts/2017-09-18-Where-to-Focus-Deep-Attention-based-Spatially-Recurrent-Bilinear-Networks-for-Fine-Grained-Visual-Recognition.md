---
layout: post
title: "Where to Focus: Deep Attention-based Spatially Recurrent Bilinear Networks for Fine-Grained Visual Recognition"
date: 2017-09-18 03:56:08
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Attention Person_Re-identification CNN Image_Classification RNN Classification Detection Recognition
author: Lin Wu, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained visual recognition typically depends on modeling subtle difference from object parts. However, these parts often exhibit dramatic visual variations such as occlusions, viewpoints, and spatial transformations, making it hard to detect. In this paper, we present a novel attention-based model to automatically, selectively and accurately focus on critical object regions with higher importance against appearance variations. Given an image, two different Convolutional Neural Networks (CNNs) are constructed, where the outputs of two CNNs are correlated through bilinear pooling to simultaneously focus on discriminative regions and extract relevant features. To capture spatial distributions among the local regions with visual attention, soft attention based spatial Long-Short Term Memory units (LSTMs) are incorporated to realize spatially recurrent yet visually selective over local input patterns. All the above intuitions equip our network with the following novel model: two-stream CNN layers, bilinear pooling layer, spatial recurrent layer with location attention are jointly trained via an end-to-end fashion to serve as the part detector and feature extractor, whereby relevant features are localized and extracted attentively. We show the significance of our network against two well-known visual recognition tasks: fine-grained image classification and person re-identification.

##### Abstract (translated by Google)
细粒度的视觉识别通常依赖于建模与对象部分的细微差别。然而，这些部分往往表现出戏剧性的视觉变化，如遮挡，观点和空间转换，使得很难检测。在本文中，我们提出了一种新型的基于注意力的模型来自动，选择性和准确地关注对外观变化具有较高重要性的关键对象区域。给定一个图像，构造两个不同的卷积神经网络（CNN），其中两个CNN的输出通过双线性汇聚相关，以同时关注区分区域并提取相关特征。为了捕捉局部区域的视觉注意力的空间分布，基于软注意的空间长 - 短期记忆单元（LSTM）被合并以实现空间循环，但视觉选择性超过局部输入模式。以上所有的直观思想使得我们的网络具有以下新颖的模型：双流CNN层，双线性汇聚层，位置注意的空间复现层通过端到端的方式联合训练，作为部分检测器和特征提取器，由此相关的特征被定位和提取注意力。我们展示了我们的网络对两个着名的视觉识别任务的重要性：细粒度图像分类和人员重新识别。

##### URL
[https://arxiv.org/abs/1709.05769](https://arxiv.org/abs/1709.05769)

##### PDF
[https://arxiv.org/pdf/1709.05769](https://arxiv.org/pdf/1709.05769)

