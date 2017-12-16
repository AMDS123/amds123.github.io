---
layout: post
title: "A Digital Fuzzy Edge Detector for Color Images"
date: 2017-01-13 05:17:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Yuan-Hang Zhang, Xie Li, Jing-Yun Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Edge detection is a classic problem in the field of image processing, which lays foundations for other tasks such as image segmentation. Conventionally, this operation is performed using gradient operators such as the Roberts or Sobel operator, which can discover local changes in intensity levels. These operators, however, perform poorly on low contrast images. In this paper, we propose an edge detector architecture for color images based on fuzzy theory and the Sobel operator. First, the R, G and B channels are extracted from an image and enhanced using fuzzy methods, in order to suppress noise and improve the contrast between the background and the objects. The Sobel operator is then applied to each of the channels, which are finally combined into an edge map of the origin image. Experimental results obtained through an FPGA-based implementation have proved the proposed method effective.

##### Abstract (translated by Google)
边缘检测是图像处理领域的一个经典问题，为图像分割等其他任务奠定了基础。通常，使用诸如罗伯茨（Roberts）或索贝尔（Sobel）算子的梯度算子来执行该操作，其可以发现强度级别的局部变化。然而，这些操作者在低对比度图像上表现不佳。在本文中，我们提出了一种基于模糊理论和Sobel算子的彩色图像边缘检测器体系结构。首先，从图像中提取R，G和B通道，并使用模糊方法进行增强，以便抑制噪声并提高背景与对象之间的对比度。然后将Sobel算子应用于每个通道，最后将这些通道组合成原始图像的边缘图。基于FPGA实现的实验结果证明了该方法的有效性。

##### URL
[https://arxiv.org/abs/1701.03364](https://arxiv.org/abs/1701.03364)

##### PDF
[https://arxiv.org/pdf/1701.03364](https://arxiv.org/pdf/1701.03364)

