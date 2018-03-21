---
layout: post
title: "Weakly Supervised Object Localization on grocery shelves using simple FCN and Synthetic Dataset"
date: 2018-03-19 06:34:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised CNN Image_Classification Classification Detection
author: Srikrishna Varadarajan, Muktabh Mayank Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a weakly supervised method using two algorithms to predict object bounding boxes given only an image classification dataset. First algorithm is a simple Fully Convolutional Network (FCN) trained to classify object instances. We use the property of FCN to return a mask for images larger than training images to get a primary output segmentation mask during test time by passing an image pyramid to it. We enhance the FCN output mask into final output bounding boxes by a Convolutional Encoder-Decoder (ConvAE) viz. the second algorithm. ConvAE is trained to localize objects on an artificially generated dataset of output segmentation masks. We demonstrate the effectiveness of this method in localizing objects in grocery shelves where annotating data for object detection is hard due to variety of objects. This method can be extended to any problem domain where collecting images of objects is easy and annotating their coordinates is hard.

##### Abstract (translated by Google)
我们提出了一种弱监督方法，使用两种算法来预测仅给定图像分类数据集的对象边界框。第一种算法是训练用来分类对象实例的简单全卷积网络（FCN）。我们使用FCN属性为图像返回一个蒙版，使图像大于训练图像，以便在测试期间通过向图像金字塔传递图像金字塔来获得主输出分割蒙版。我们通过卷积编码器 - 解码器（ConvAE）即将FCN输出掩模增强为最终输出边界框。第二种算法。 ConvAE经过训练，可以将人工生成的输出分割蒙版数据集上的对象进行本地化。我们证明了这种方法在杂货架上定位物体时的有效性，其中由于各种物体的缘故，用于物体检测的注释数据很难。这种方法可以扩展到任何问题域，其中收集对象的图像很容易，并且注释它们的坐标是困难的。

##### URL
[https://arxiv.org/abs/1803.06813](https://arxiv.org/abs/1803.06813)

##### PDF
[https://arxiv.org/pdf/1803.06813](https://arxiv.org/pdf/1803.06813)

