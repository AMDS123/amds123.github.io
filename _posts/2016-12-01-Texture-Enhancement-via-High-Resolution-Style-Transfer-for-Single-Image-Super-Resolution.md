---
layout: post
title: "Texture Enhancement via High-Resolution Style Transfer for Single-Image Super-Resolution"
date: 2016-12-01 00:15:02
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Style_Transfer
author: Il Jun Ahn (1), Woo Hyun Nam (1) ((1) Digital Media & Communications R&D Center, Samsung Electronics, Seoul, Korea)
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, various deep-neural-network (DNN)-based approaches have been proposed for single-image super-resolution (SISR). Despite their promising results on major structure regions such as edges and lines, they still suffer from limited performance on texture regions that consist of very complex and fine patterns. This is because, during the acquisition of a low-resolution (LR) image via down-sampling, these regions lose most of the high frequency information necessary to represent the texture details. In this paper, we present a novel texture enhancement framework for SISR to effectively improve the spatial resolution in the texture regions as well as edges and lines. We call our method, high-resolution (HR) style transfer algorithm. Our framework consists of three steps: (i) generate an initial HR image from an interpolated LR image via an SISR algorithm, (ii) generate an HR style image from the initial HR image via down-scaling and tiling, and (iii) combine the HR style image with the initial HR image via a customized style transfer algorithm. Here, the HR style image is obtained by down-scaling the initial HR image and then repetitively tiling it into an image of the same size as the HR image. This down-scaling and tiling process comes from the idea that texture regions are often composed of small regions that similar in appearance albeit sometimes different in scale. This process creates an HR style image that is rich in details, which can be used to restore high-frequency texture details back into the initial HR image via the style transfer algorithm. Experimental results on a number of texture datasets show that our proposed HR style transfer algorithm provides more visually pleasing results compared with competitive methods.

##### Abstract (translated by Google)
近来，已经提出了各种基于深度神经网络（DNN）的单图像超分辨率（SISR）方法。尽管在主要结构区域（如边缘和线条）上取得了令人满意的结果，但在由非常复杂和精细的图案组成的纹理区域上仍然受到有限的性能影响。这是因为，在通过下采样获取低分辨率（LR）图像期间，这些区域失去了表示纹理细节所必需的大部分高频信息。在本文中，我们提出了一种新的纹理增强框架SISR有效地提高纹理区域以及边缘和线条的空间分辨率。我们称之为我们的方法，即高分辨率（HR）式的传输算法。我们的框架由三个步骤组成：（i）通过SISR算法从插值LR图像生成初始HR图像，（ii）通过缩小和平铺从初始HR图像生成HR样式图像，以及（iii）组合通过定制的样式转移算法将具有初始HR图像的HR样式图像。这里，通过缩小初始HR图像，然后将其重复平铺成与HR图像相同尺寸的图像来获得HR风格图像。这种缩小和拼贴的过程来自纹理区域通常由小区域构成的想法，虽然有时在尺寸上有所不同，但外观相似。这个过程创建了一个细节丰富的HR样式图像，可以通过样式转换算法将高频纹理细节恢复到初始HR图像。在一些纹理数据集上的实验结果表明，我们提出的HR样式转换算法比竞争方法提供了更多的视觉愉悦的结果。

##### URL
[https://arxiv.org/abs/1612.00085](https://arxiv.org/abs/1612.00085)

##### PDF
[https://arxiv.org/pdf/1612.00085](https://arxiv.org/pdf/1612.00085)

