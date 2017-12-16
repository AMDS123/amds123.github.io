---
layout: post
title: "A learning-based approach for automatic image and video colorization"
date: 2017-04-15 09:21:57
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Raj Kumar Gupta, Alex Yong-Sang Chia, Deepu Rajan, Huang Zhiyong
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a color transfer algorithm to colorize a broad range of gray images without any user intervention. The algorithm uses a machine learning-based approach to automatically colorize grayscale images. The algorithm uses the superpixel representation of the reference color images to learn the relationship between different image features and their corresponding color values. We use this learned information to predict the color value of each grayscale image superpixel. As compared to processing individual image pixels, our use of superpixels helps us to achieve a much higher degree of spatial consistency as well as speeds up the colorization process. The predicted color values of the gray-scale image superpixels are used to provide a 'micro-scribble' at the centroid of the superpixels. These color scribbles are refined by using a voting based approach. To generate the final colorization result, we use an optimization-based approach to smoothly spread the color scribble across all pixels within a superpixel. Experimental results on a broad range of images and the comparison with existing state-of-the-art colorization methods demonstrate the greater effectiveness of the proposed algorithm.

##### Abstract (translated by Google)
在本文中，我们提出了一种颜色转换算法，使大量的灰度图像着色，而无需用户干预。该算法使用基于机器学习的方法来自动着色灰度图像。该算法使用参考彩色图像的超像素表示来学习不同图像特征与其对应颜色值之间的关系。我们使用这个学到的信息来预测每个灰度图像超像素的颜色值。与处理单个图像像素相比，我们使用超像素有助于我们实现更高程度的空间一致性，并加快着色过程。灰度图像超像素的预测颜色值用于在超像素的质心上提供“微观涂抹”。这些颜色涂鸦是通过使用基于投票的方法来完善的。为了生成最终的着色结果，我们使用基于优化的方法来平滑地在超像素内的所有像素上散布彩色涂鸦。在广泛的图像上的实验结果以及与现有的现有技术的着色方法的比较证明了所提出的算法的更大有效性。

##### URL
[https://arxiv.org/abs/1704.04610](https://arxiv.org/abs/1704.04610)

##### PDF
[https://arxiv.org/pdf/1704.04610](https://arxiv.org/pdf/1704.04610)

