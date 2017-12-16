---
layout: post
title: "Setting an attention region for convolutional neural networks using region selective features, for recognition of materials within glass vessels"
date: 2017-09-09 19:25:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Classification Recognition
author: Sagi Eppel
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have emerged as the leading method for the classification and segmentation of images. In some cases, it is desirable to focus the attention of the net on a specific region in the image; one such case is the recognition of the contents of transparent vessels, where the vessel region in the image is already known. This work presents a valve filter approach for focusing the attention of the net on a region of interest (ROI). In this approach, the ROI is inserted into the net as a binary map. The net uses a different set of convolution filters for the ROI and background image regions, resulting in a different set of features being extracted from each region. More accurately, for each filter used on the image, a corresponding valve filter exists that acts on the ROI map and determines the regions in which the corresponding image filter will be used. This valve filter effectively acts as a valve that inhibits specific features in different image regions according to the ROI map. In addition, a new data set for images of materials in glassware vessels in a chemistry laboratory setting is presented. This data set contains a thousand images with pixel-wise annotation according to categories ranging from filled and empty to the exact phase of the material inside the vessel. The results of the valve filter approach and fully convolutional neural nets (FCN) with no ROI input are compared based on this data set.

##### Abstract (translated by Google)
卷积神经网络已经成为图像分类和分割的主要方法。在某些情况下，最好将网络的注意力集中在图像中的特定区域;一个这样的情况是识别透明容器的内容，其中图像中的容器区域已经是已知的。这项工作提出了一个阀门过滤器的方法，把注意力集中在一个感兴趣区域（ROI）上。在这种方法中，ROI作为二进制映射插入到网络中。网络为ROI和背景图像区域使用不同的卷积滤波器组，从而导致从每个区域提取不同的特征组。更准确地说，对于在图像上使用的每个滤波器，存在相应的阀滤波器，其作用在ROI图上并确定将使用相应图像滤波器的区域。根据ROI图，该阀过滤器有效地用作抑制不同图像区域中的特定特征的阀。此外，还介绍了化学实验室中用于玻璃容器中材料图像的新数据集。该数据集包含一千个图像，其中按照从填充和空到类别内的物质的准确阶段的类别进行按像素注释。基于这个数据集比较了阀门过滤器方法和没有ROI输入的完全卷积神经网络（FCN）的结果。

##### URL
[https://arxiv.org/abs/1708.08711](https://arxiv.org/abs/1708.08711)

##### PDF
[https://arxiv.org/pdf/1708.08711](https://arxiv.org/pdf/1708.08711)

