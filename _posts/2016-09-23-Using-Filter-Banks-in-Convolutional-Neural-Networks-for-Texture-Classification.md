---
layout: post
title: "Using Filter Banks in Convolutional Neural Networks for Texture Classification"
date: 2016-09-23 09:20:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Speech_Recognition CNN Classification Deep_Learning Detection Recognition
author: Vincent Andrearczyk, Paul F. Whelan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has established many new state of the art solutions in the last decade in areas such as object, scene and speech recognition. In particular Convolutional Neural Network (CNN) is a category of deep learning which obtains excellent results in object detection and recognition tasks. Its architecture is indeed well suited to object analysis by learning and classifying complex (deep) features that represent parts of an object or the object itself. However, some of its features are very similar to texture analysis methods. CNN layers can be thought of as filter banks of complexity increasing with the depth. Filter banks are powerful tools to extract texture features and have been widely used in texture analysis. In this paper we develop a simple network architecture named Texture CNN (T-CNN) which explores this observation. It is built on the idea that the overall shape information extracted by the fully connected layers of a classic CNN is of minor importance in texture analysis. Therefore, we pool an energy measure from the last convolution layer which we connect to a fully connected layer. We show that our approach can improve the performance of a network while greatly reducing the memory usage and computation.

##### Abstract (translated by Google)
深度学习在过去的十年中已经在对象，场景和语音识别等领域建立了许多新的最先进的解决方案。特别是卷积神经网络（CNN）是深度学习的一个类别，在物体检测和识别任务中取得了优异的成果。通过学习和分类代表对象或对象本身的复杂（深层）特征，其架构确实非常适合对象分析。但是，它的一些特征与纹理分析方法非常相似。 CNN层可以被认为是复杂度随着深度增加的滤波器组。滤波器组是提取纹理特征的有力工具，并已被广泛用于纹理分析。在本文中，我们开发了一个名为Texture CNN（T-CNN）的简单网络体系结构，探讨了这个观察。它是建立在这样一个想法，即一个经典CNN的完全连接层提取的整体形状信息在纹理分析中是次要的。因此，我们将最后一个卷积层的能量度量集中到一个完全连通的层上。我们表明，我们的方法可以提高网络的性能，同时大大减少内存使用和计算。

##### URL
[https://arxiv.org/abs/1601.02919](https://arxiv.org/abs/1601.02919)

##### PDF
[https://arxiv.org/pdf/1601.02919](https://arxiv.org/pdf/1601.02919)

