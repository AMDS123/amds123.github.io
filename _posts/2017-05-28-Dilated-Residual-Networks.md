---
layout: post
title: "Dilated Residual Networks"
date: 2017-05-28 09:01:44
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Fisher Yu, Vladlen Koltun, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks for image classification progressively reduce resolution until the image is represented by tiny feature maps in which the spatial structure of the scene is no longer discernible. Such loss of spatial acuity can limit image classification accuracy and complicate the transfer of the model to downstream applications that require detailed scene understanding. These problems can be alleviated by dilation, which increases the resolution of output feature maps without reducing the receptive field of individual neurons. We show that dilated residual networks (DRNs) outperform their non-dilated counterparts in image classification without increasing the model's depth or complexity. We then study gridding artifacts introduced by dilation, develop an approach to removing these artifacts (`degridding'), and show that this further increases the performance of DRNs. In addition, we show that the accuracy advantage of DRNs is further magnified in downstream applications such as object localization and semantic segmentation.

##### Abstract (translated by Google)
用于图像分类的卷积网络逐渐降低分辨率，直到图像由其中场景的空间结构不再可辨别的微小特征图表示。空间敏锐度的这种损失会限制图像分类的准确性，并使得模型向需要详细场景理解的下游应用转移复杂化。这些问题可以通过扩张来缓解，这增加了输出特征图的分辨率，而不会降低单个神经元的感受野。我们表明，膨胀的残留网络（DRNs）在图像分类方面优于非扩张的网络，而不增加模型的深度或复杂度。然后，我们研究通过膨胀引入的网格工件，开发一种消除这些工件的方法（`degridding'），并且显示这进一步提高了DRN的性能。另外，我们还发现DRN的准确性优势在对象定位和语义分割等下游应用中进一步放大。

##### URL
[https://arxiv.org/abs/1705.09914](https://arxiv.org/abs/1705.09914)

##### PDF
[https://arxiv.org/pdf/1705.09914](https://arxiv.org/pdf/1705.09914)

