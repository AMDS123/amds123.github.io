---
layout: post
title: "Color Image Enhancement Using the lrgb Coordinates in the Context of Support Fuzzification"
date: 2015-02-16 11:32:00
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement
author: Vasile Patrascu
mathjax: true
---

* content
{:toc}

##### Abstract
Image enhancement is an important stage in the image-processing domain. The most known image enhancement method is the histogram equalization. This method is an automated one, and realizes a simultaneous modification for brightness and contrast in the case of monochrome images and for brightness, contrast, saturation and hue in the case of color images. Simple and efficient methods can be obtained if affine transforms within logarithmic models are used. A very important thing in the affine transform determination for color images is the coordinate system that is used for color space representation. Thus, the using of the RGB coordinates leads to a simultaneous modification of luminosity and saturation. In this paper using the lrgb perceptual coordinates one can define affine transforms, which allow a separated modification of luminosity l and saturation s (saturation being calculated with the component rgb in the chromatic plane). Better results can be obtained if partitions are defined on the image support and then the pixels are separately processed in each window belonging to the defined partition. Classical partitions frequently lead to the appearance of some discontinuities at the boundaries between these windows. In order to avoid all these drawbacks the classical partitions may be replaced by fuzzy partitions. Their elements will be fuzzy windows and in each of them there will be defined an affine transform induced by parameters using the fuzzy mean, fuzzy variance and fuzzy saturation computed for the pixels that belong to the analyzed window. The final image is obtained by summing up in a weight way the images of every fuzzy window.

##### Abstract (translated by Google)
图像增强是图像处理领域的一个重要阶段。最着名的图像增强方法是直方图均衡。这种方法是自动的，在单色图像的情况下实现亮度和对比度的同时修改，在彩色图像的情况下实现亮度，对比度，饱和度和色调的同时修改。如果使用对数模型中的仿射变换，则可以获得简单而有效的方法。在彩色图像的仿射变换确定中非常重要的是用于彩色空间表示的坐标系。因此，使用RGB坐标导致同时修改亮度和饱和度。在本文中，使用lrgb感知坐标，可以定义仿射变换，这允许分离地修改亮度l和饱和度s（饱和度用色平面中的分量rgb计算）。如果在图像支持上定义了分区，然后在属于定义分区的每个窗口中单独处理像素，则可以获得更好的结果。经典的分区经常导致在这些窗口之间的边界处出现一些不连续性。为了避免所有这些缺点，传统的分区可能被模糊分区所取代。它们的元素将是模糊窗口，并且在它们中的每一个中将定义由参数引起的仿射变换，使用针对属于分析窗口的像素计算的模糊均值，模糊方差和模糊饱和度。最终的图像是通过加权求和每个模糊窗口的图像而获得的。

##### URL
[https://arxiv.org/abs/1502.04499](https://arxiv.org/abs/1502.04499)

##### PDF
[https://arxiv.org/pdf/1502.04499](https://arxiv.org/pdf/1502.04499)

