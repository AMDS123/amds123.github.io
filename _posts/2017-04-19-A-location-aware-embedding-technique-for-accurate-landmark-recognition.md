---
layout: post
title: "A location-aware embedding technique for accurate landmark recognition"
date: 2017-04-19 14:45:23
categories: arXiv_CV
tags: arXiv_CV Embedding Recognition
author: Federico Magliani, Navid Mahmoudian Bidgoli, Andrea Prati
mathjax: true
---

* content
{:toc}

##### Abstract
The current state of the research in landmark recognition highlights the good accuracy which can be achieved by embedding techniques, such as Fisher vector and VLAD. All these techniques do not exploit spatial information, i.e. consider all the features and the corresponding descriptors without embedding their location in the image. This paper presents a new variant of the well-known VLAD (Vector of Locally Aggregated Descriptors) embedding technique which accounts, at a certain degree, for the location of features. The driving motivation comes from the observation that, usually, the most interesting part of an image (e.g., the landmark to be recognized) is almost at the center of the image, while the features at the borders are irrelevant features which do no depend on the landmark. The proposed variant, called locVLAD (location-aware VLAD), computes the mean of the two global descriptors: the VLAD executed on the entire original image, and the one computed on a cropped image which removes a certain percentage of the image borders. This simple variant shows an accuracy greater than the existing state-of-the-art approach. Experiments are conducted on two public datasets (ZuBuD and Holidays) which are used both for training and testing. Morever a more balanced version of ZuBuD is proposed.

##### Abstract (translated by Google)
地标识别研究的当前状态突出了通过嵌入技术（如Fisher矢量和VLAD）可以实现的高精度。所有这些技术都不利用空间信息，即考虑所有的特征和相应的描述符而不将它们的位置嵌入到图像中。本文提出了一个着名的VLAD（局部聚合描述符向量）嵌入技术的新变种，它在一定程度上说明了特征的位置。驾驶动机来自观察，通常，图像中最有趣的部分（例如被识别的地标）几乎处于图像的中心，而边界处的特征是不依赖于特征的无关特征地标。提出的变种叫做locVLAD（位置感知型VLAD），计算两个全局描述符的平均值：在整个原始图像上执行的VLAD，以及在裁剪的图像上计算的VLAD，该图像去除了一定比例的图像边界。这个简单的变体显示比现有的最先进的方法更高的精度。实验在两个公共数据集（ZuBuD和Holidays）上进行，这两个数据集用于训练和测试。另外还提​​出了更为平衡的ZuBuD版本。

##### URL
[https://arxiv.org/abs/1704.05754](https://arxiv.org/abs/1704.05754)

##### PDF
[https://arxiv.org/pdf/1704.05754](https://arxiv.org/pdf/1704.05754)

