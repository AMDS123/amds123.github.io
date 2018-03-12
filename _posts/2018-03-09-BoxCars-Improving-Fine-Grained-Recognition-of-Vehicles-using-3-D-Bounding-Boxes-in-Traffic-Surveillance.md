---
layout: post
title: "BoxCars: Improving Fine-Grained Recognition of Vehicles using 3-D Bounding Boxes in Traffic Surveillance"
date: 2018-03-09 12:01:57
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Jakub Sochor, Jakub &#x160;pa&#x148;hel, Adam Herout
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on fine-grained recognition of vehicles mainly in traffic surveillance applications. We propose an approach that is orthogonal to recent advancements in fine-grained recognition (automatic part discovery and bilinear pooling). In addition, in contrast to other methods focused on fine-grained recognition of vehicles, we do not limit ourselves to a frontal/rear viewpoint, but allow the vehicles to be seen from any viewpoint. Our approach is based on 3-D bounding boxes built around the vehicles. The bounding box can be automatically constructed from traffic surveillance data. For scenarios where it is not possible to use precise construction, we propose a method for an estimation of the 3-D bounding box. The 3-D bounding box is used to normalize the image viewpoint by "unpacking" the image into a plane. We also propose to randomly alter the color of the image and add a rectangle with random noise to a random position in the image during the training of convolutional neural networks (CNNs). We have collected a large fine-grained vehicle data set BoxCars116k, with 116k images of vehicles from various viewpoints taken by numerous surveillance cameras. We performed a number of experiments, which show that our proposed method significantly improves CNN classification accuracy (the accuracy is increased by up to 12% points and the error is reduced by up to 50% compared with CNNs without the proposed modifications). We also show that our method outperforms the state-of-the-art methods for fine-grained recognition.

##### Abstract (translated by Google)
在本文中，我们主要关注交通监控应用中车辆的细粒度识别。我们提出了一种与细粒度识别（自动部分发现和双线性池化）最近进展正交的方法。此外，与专注于车辆细粒度识别的其他方法相比，我们不会将自己限制在前/后视点，而是允许从任何视角看车辆。我们的方法基于车辆周围的三维边界框。边界框可以根据交通监控数据自动构建。对于无法使用精确构造的场景，我们提出了一种估算三维边界框的方法。三维边界框用于通过将图像“解包”到平面中来规范图像视点。我们还建议在卷积神经网络（CNN）的训练过程中随机改变图像的颜色，并将随机噪声的矩形添加到图像中的随机位置。我们收集了一个大型的细粒度车辆数据集BoxCars116k，其中有来自众多监控摄像头拍摄的来自不同视角的车辆116k幅图像。我们进行了大量实验，这些实验表明，我们提出的方法显着提高了CNN分类的准确性（与没有提出修改的CNN相比，准确度提高了12％，误差降低了50％）。我们还表明，我们的方法胜过了用于细粒度识别的最先进的方法。

##### URL
[http://arxiv.org/abs/1703.00686](http://arxiv.org/abs/1703.00686)

##### PDF
[http://arxiv.org/pdf/1703.00686](http://arxiv.org/pdf/1703.00686)

