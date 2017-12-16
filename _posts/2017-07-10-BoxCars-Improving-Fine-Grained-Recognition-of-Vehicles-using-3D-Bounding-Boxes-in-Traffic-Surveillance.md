---
layout: post
title: "BoxCars: Improving Fine-Grained Recognition of Vehicles using 3D Bounding Boxes in Traffic Surveillance"
date: 2017-07-10 08:23:55
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Jakub Sochor, Jakub Špaňhel, Adam Herout
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on fine-grained recognition of vehicles mainly in traffic surveillance applications. We propose an approach orthogonal to recent advancement in fine-grained recognition (automatic part discovery, bilinear pooling). Also, in contrast to other methods focused on fine-grained recognition of vehicles, we do not limit ourselves to frontal/rear viewpoint but allow the vehicles to be seen from any viewpoint. Our approach is based on 3D bounding boxes built around the vehicles. The bounding box can be automatically constructed from traffic surveillance data. For scenarios where it is not possible to use the precise construction, we propose a method for estimation of the 3D bounding box. The 3D bounding box is used to normalize the image viewpoint by "unpacking" the image into plane. We also propose to randomly alter the color of the image and add a rectangle with random noise to random position in the image during training Convolutional Neural Networks. We have collected a large fine-grained vehicle dataset BoxCars116k, with 116k images of vehicles from various viewpoints taken by numerous surveillance cameras. We performed a number of experiments which show that our proposed method significantly improves CNN classification accuracy (the accuracy is increased by up to 12 percent points and the error is reduced by up to 50% compared to CNNs without the proposed modifications). We also show that our method outperforms state-of-the-art methods for fine-grained recognition.

##### Abstract (translated by Google)
在本文中，我们主要关注车辆的细粒度识别，主要在交通监控应用中。我们提出了一种正交于细粒度识别（自动部分发现，双线性池）的近期进展的方法。此外，与其他方法集中在车辆的细粒度识别相反，我们不限于前/后视点，而是允许从任何角度看车辆。我们的方法是基于车辆周围的3D边界框。边界框可以根据交通监控数据自动构建。对于不可能使用精确构造的场景，我们提出了一种估算三维边界框的方法。 3D边界框用于通过将图像“解包”成平面来对图像视点进行归一化。我们还建议在训练卷积神经网络时，随机改变图像的颜色，并在图像中随机添加一个带有随机噪声的矩形。我们收集了一个大型的细粒度车辆数据集BoxCars116k，其中有来自众多监控摄像机拍摄的各种视角的车辆116k幅图像。我们进行了大量的实验，结果表明，我们提出的方法显着提高了CNN分类的准确性（与未提出修改的CNN相比，准确度提高了12个百分点，误差降低了50％）。我们还表明，我们的方法胜过了最先进的细粒度识别方法。

##### URL
[https://arxiv.org/abs/1703.00686](https://arxiv.org/abs/1703.00686)

##### PDF
[https://arxiv.org/pdf/1703.00686](https://arxiv.org/pdf/1703.00686)

