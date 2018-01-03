---
layout: post
title: "Fractional Local Neighborhood Intensity Pattern for Image Retrieval using Genetic Algorithm"
date: 2017-12-30 20:18:32
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Relation
author: Avirup Bhattacharyya, Ayan Kumar Bhunia, Prithaj Banerjee, Partha Pratim Roy, Subrahmanyam Murala
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a new texture descriptor named "Fractional Local Neighborhood Intensity Pattern" (FLNIP) has been proposed for content based image retrieval (CBIR). It is an extension of the Local Neighborhood Intensity Pattern (LNIP)[1]. FLNIP calculates the relative intensity difference between a particular pixel and the center pixel of a 3x3 window by considering the relationship with adjacent neighbors. In this work, the fractional change in the local neighborhood involving the adjacent neighbors has been calculated first with respect to one of the eight neighbors of the center pixel of a 3x3 window. Next, the fractional change has been calculated with respect to the center itself. The two values of fractional change are next compared to generate a binary bit pattern. Both sign and magnitude information are encoded in a single descriptor as it deals with the relative change in magnitude in the adjacent neighborhood i.e., the comparison of the fractional change. The descriptor is applied on four multi-resolution images- one being the raw image and the other three being filtered gaussian images obtained by applying gaussian filters of different standard deviations on the raw image to signify the importance of exploring texture information at different resolutions in an image. The four sets of distances obtained between the query and the target image are then combined with a genetic algorithm based approach to improve the retrieval performance by minimizing the distance between similar class images. The performance of the method has been tested for image retrieval on four popular databases. The precision and recall values observed on these databases have been compared with recent state-of-art local patterns. The proposed method has shown a significant improvement over many other existing methods.

##### Abstract (translated by Google)
本文提出了一种新的基于内容的图像检索（CBIR）的纹理描述符“分数局部邻域强度模式”（FLNIP）。它是当地邻里强度模式（LNIP）的延伸[1]。 FLNIP通过考虑与相邻邻居的关系来计算特定像素与3x3窗口的中心像素之间的相对强度差异。在这项工作中，涉及邻近邻居的局部邻域的分数变化已经首先相对于3×3窗口的中心像素的八个邻居中的一个来计算。接下来，已经针对中心本身计算了分数变化。接下来比较分数变化的两个值以生成二进制位模式。符号和大小信息都被编码在单个描述符中，因为它处理相邻邻域中幅值的相对变化，即分数变化的比较。描述符应用于四个多分辨率图像 - 一个是原始图像，另三个是通过对原始图像应用不同标准偏差的高斯滤波器获得的滤波的高斯图像，以表示在不同分辨率下探测纹理信息的重要性图片。然后将查询与目标图像之间获得的四组距离与基于遗传算法的方法相结合，以通过最小化类似图像之间的距离来提高检索性能。该方法的性能已经在四个流行的数据库上进行了图像检索的测试。在这些数据库中观察到的精确度和召回率值已经与最近的最新的本地模式进行了比较。所提出的方法已经显示出比许多其他现有方法显着的改进。

##### URL
[http://arxiv.org/abs/1801.00187](http://arxiv.org/abs/1801.00187)

##### PDF
[http://arxiv.org/pdf/1801.00187](http://arxiv.org/pdf/1801.00187)

