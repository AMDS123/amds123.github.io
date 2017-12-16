---
layout: post
title: "Digital Makeup from Internet Images"
date: 2016-12-29 12:59:37
categories: arXiv_CV
tags: arXiv_CV Face
author: Asad Khan, Muhammad Ahmad, Yudong Guo, Ligang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach of color transfer between images by exploring their high-level semantic information. First, we set up a database which consists of the collection of downloaded images from the internet, which are segmented automatically by using matting techniques. We then, extract image foregrounds from both source and multiple target images. Then by using image matting algorithms, the system extracts the semantic information such as faces, lips, teeth, eyes, eyebrows, etc., from the extracted foregrounds of the source image. And, then the color is transferred between corresponding parts with the same semantic information. Next we get the color transferred result by seamlessly compositing different parts together using alpha blending. In the final step, we present an efficient method of color consistency to optimize the color of a collection of images showing the common scene. The main advantage of our method over existing techniques is that it does not need face matching, as one could use more than one target images. It is not restricted to head shot images as we can also change the color style in the wild. Moreover, our algorithm does not require to choose the same color style, same pose and image size between source and target images. Our algorithm is not restricted to one-to-one image color transfer and can make use of more than one target images to transfer the color in different parts in the source image. Comparing with other approaches, our algorithm is much better in color blending in the input data.

##### Abstract (translated by Google)
通过探索高级语义信息，提出了一种图像间颜色转换的新方法。首先，我们建立了一个数据库，它由从网上下载的图像集合组成，这些图像通过使用消光技术自动分割。然后，我们从源和多个目标图像中提取图像前景。然后，利用图像拼接算法从提取的源图像前景中提取面部，嘴唇，牙齿，眼睛，眉毛等语义信息。然后，颜色在具有相同语义信息的相应部分之间转移。接下来，我们通过使用alpha混合将不同部分无缝合成，从而获得颜色传输结果。在最后一步，我们提出了一种有效的颜色一致性方法来优化显示常见场景的图像集合的颜色。我们的方法相对于现有技术的主要优点是不需要面对匹配，因为可以使用多个目标图像。它不限于头部拍摄的图像，因为我们也可以改变野外的颜色风格。此外，我们的算法不需要选择源图像和目标图像之间相同的颜色风格，相同的姿势和图像大小。我们的算法并不局限于一对一的图像色彩转移，而是可以利用多个目标图像来转换源图像中不同部分的颜色。与其他方法相比，我们的算法在输入数据的颜色混合方面要好得多。

##### URL
[https://arxiv.org/abs/1610.04861](https://arxiv.org/abs/1610.04861)

##### PDF
[https://arxiv.org/pdf/1610.04861](https://arxiv.org/pdf/1610.04861)

