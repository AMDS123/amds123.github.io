---
layout: post
title: "Warped Convolutions: Efficient Invariance to Spatial Transformations"
date: 2016-11-04 20:06:59
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning
author: João F. Henriques, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are extremely efficient, since they exploit the inherent translation-invariance of natural images. However, translation is just one of a myriad of useful spatial transformations. Can the same efficiency be attained when considering other spatial invariances? Such generalized convolutions have been considered in the past, but at a high computational cost. We present a construction that is simple and exact, yet has the same computational complexity that standard convolutions enjoy. It consists of a constant image warp followed by a simple convolution, which are standard blocks in deep learning toolboxes. With a carefully crafted warp, the resulting architecture can be made invariant to one of a wide range of spatial transformations. We show encouraging results in realistic scenarios, including the estimation of vehicle poses in the Google Earth dataset (rotation and scale), and face poses in Annotated Facial Landmarks in the Wild (3D rotations under perspective).

##### Abstract (translated by Google)
卷积神经网络（CNN）是非常有效的，因为它们利用自然图像的固有的平移不变性。然而，翻译只是无数有用的空间转换之一。在考虑其他空间不变性时能否达到相同的效率？过去已经考虑过这种广义卷积，但是计算成本很高。我们提出一个简单而精确的构造，但是具有与标准卷积相同的计算复杂性。它由一个恒定的图像扭曲和一个简单的卷积组成，它们是深度学习工具箱中的标准块。通过精心制作的经纱，所得到的结构可以在广泛的空间变换之一中不变。我们在逼真的场景中展示了令人鼓舞的结果，其中包括估算Google Earth数据集中的车辆姿势（旋转和缩放）以及野外注释的面部标志（透视下的3D旋转）中的脸部姿势。

##### URL
[https://arxiv.org/abs/1609.04382](https://arxiv.org/abs/1609.04382)

##### PDF
[https://arxiv.org/pdf/1609.04382](https://arxiv.org/pdf/1609.04382)

