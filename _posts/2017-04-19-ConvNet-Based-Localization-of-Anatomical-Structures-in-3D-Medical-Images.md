---
layout: post
title: "ConvNet-Based Localization of Anatomical Structures in 3D Medical Images"
date: 2017-04-19 06:54:34
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Bob D. de Vos, Jelmer M. Wolterink, Pim A. de Jong, Tim Leiner, Max A. Viergever, Ivana Išgum
mathjax: true
---

* content
{:toc}

##### Abstract
Localization of anatomical structures is a prerequisite for many tasks in medical image analysis. We propose a method for automatic localization of one or more anatomical structures in 3D medical images through detection of their presence in 2D image slices using a convolutional neural network (ConvNet). A single ConvNet is trained to detect presence of the anatomical structure of interest in axial, coronal, and sagittal slices extracted from a 3D image. To allow the ConvNet to analyze slices of different sizes, spatial pyramid pooling is applied. After detection, 3D bounding boxes are created by combining the output of the ConvNet in all slices. In the experiments 200 chest CT, 100 cardiac CT angiography (CTA), and 100 abdomen CT scans were used. The heart, ascending aorta, aortic arch, and descending aorta were localized in chest CT scans, the left cardiac ventricle in cardiac CTA scans, and the liver in abdomen CT scans. Localization was evaluated using the distances between automatically and manually defined reference bounding box centroids and walls. The best results were achieved in localization of structures with clearly defined boundaries (e.g. aortic arch) and the worst when the structure boundary was not clearly visible (e.g. liver). The method was more robust and accurate in localization multiple structures.

##### Abstract (translated by Google)
解剖结构的定位是医学图像分析中许多任务的先决条件。我们提出了一种方法，通过使用卷积神经网络（ConvNet）在二维图像切片中检测它们的存在来自动定位三维医学图像中的一个或多个解剖结构。训练单个ConvNet以检测从3D图像提取的轴向，冠状和矢状切片中感兴趣的解剖结构的存在。为了允许ConvNet分析不同大小的切片，应用空间金字塔池。在检测之后，通过结合所有切片中的ConvNet的输出来创建3D边界框。在实验中，使用了200次胸部CT，100次心脏CT血管造影（CTA）和100次腹部CT扫描。心脏，升主动脉，主动脉弓和降主动脉定位于胸部CT扫描，左心室心脏CTA扫描以及腹部CT扫描。使用自动和手动定义的参考边界框质心和壁之间的距离来评估本地化。在具有清晰界定的结构（例如主动脉弓）的结构的定位方面取得了最好的结果，而当结构边界不清晰可见时（例如肝脏）则是最差的。该方法在定位多结构中更加健壮和准确。

##### URL
[https://arxiv.org/abs/1704.05629](https://arxiv.org/abs/1704.05629)

##### PDF
[https://arxiv.org/pdf/1704.05629](https://arxiv.org/pdf/1704.05629)

