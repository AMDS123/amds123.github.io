---
layout: post
title: "Hyperspectral CNN Classification with Limited Training Samples"
date: 2016-11-28 07:29:29
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Lloyd Windrim, Rishi Ramakrishnan, Arman Melkumyan, Richard Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral imaging sensors are becoming increasingly popular in robotics applications such as agriculture and mining, and allow per-pixel thematic classification of materials in a scene based on their unique spectral signatures. Recently, convolutional neural networks have shown remarkable performance for classification tasks, but require substantial amounts of labelled training data. This data must sufficiently cover the variability expected to be encountered in the environment. For hyperspectral data, one of the main variations encountered outdoors is due to incident illumination, which can change in spectral shape and intensity depending on the scene geometry. For example, regions occluded from the sun have a lower intensity and their incident irradiance skewed towards shorter wavelengths. In this work, a data augmentation strategy based on relighting is used during training of a hyperspectral convolutional neural network. It allows training to occur in the outdoor environment given only a small labelled region, which does not need to sufficiently represent the geometric variability of the entire scene. This is important for applications where obtaining large amounts of training data is labourious, hazardous or difficult, such as labelling pixels within shadows. Radiometric normalisation approaches for pre-processing the hyperspectral data are analysed and it is shown that methods based on the raw pixel data are sufficient to be used as input for the classifier. This removes the need for external hardware such as calibration boards, which can restrict the application of hyperspectral sensors in robotics applications. Experiments to evaluate the classification system are carried out on two datasets captured from a field-based platform.

##### Abstract (translated by Google)
高光谱成像传感器在诸如农业和采矿等机器人应用中变得越来越流行，并且允许基于其独特的光谱特征的场景中的材料的按像素专题分类。最近，卷积神经网络在分类任务中表现出了显着的性能，但是需要大量标记的训练数据。这些数据必须足够覆盖在环境中预期会遇到的变化。对于高光谱数据，在户外遇到的主要变化之一是由于入射照明，其可根据场景几何形状改变光谱形状和强度。例如，从太阳遮挡的区域具有较低的强度，并且它们的入射辐射偏向较短的波长。在这项工作中，在高光谱卷积神经网络的训练中使用基于重照的数据增强策略。它只允许训练发生在室外环境中，只有一个小的标记区域，不需要充分表示整个场景的几何变化。这对于获取大量训练数据的应用程序非常重要，例如在阴影内标注像素。分析了用于预处理高光谱数据的辐射标准化方法，并且显示基于原始像素数据的方法足以用作分类器的输入。这消除了对校准板等外部硬件的需求，这会限制高光谱传感器在机器人应用中的应用。评估分类系统的实验是在从现场平台捕获的两个数据集上进行的。

##### URL
[https://arxiv.org/abs/1611.09007](https://arxiv.org/abs/1611.09007)

##### PDF
[https://arxiv.org/pdf/1611.09007](https://arxiv.org/pdf/1611.09007)

