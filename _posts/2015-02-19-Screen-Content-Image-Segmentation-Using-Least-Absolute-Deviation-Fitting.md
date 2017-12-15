---
layout: post
title: "Screen Content Image Segmentation Using Least Absolute Deviation Fitting"
date: 2015-02-19 07:07:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Shervin Minaee, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an algorithm for separating the foreground (mainly text and line graphics) from the smoothly varying background in screen content images. The proposed method is designed based on the assumption that the background part of the image is smoothly varying and can be represented by a linear combination of a few smoothly varying basis functions, while the foreground text and graphics create sharp discontinuity and cannot be modeled by this smooth representation. The algorithm separates the background and foreground using a least absolute deviation method to fit the smooth model to the image pixels. This algorithm has been tested on several images from HEVC standard test sequences for screen content coding, and is shown to have superior performance over other popular methods, such as k-means clustering based segmentation in DjVu and shape primitive extraction and coding (SPEC) algorithm. Such background/foreground segmentation are important pre-processing steps for text extraction and separate coding of background and foreground for compression of screen content images.

##### Abstract (translated by Google)
我们提出了一种算法，用于从屏幕内容图像的平滑变化的背景中分离前景（主要是文本和线条图形）。所提出的方法是基于这样的假设设计的，即图像的背景部分是平滑变化的，并且可以由几个平滑变化的基函数的线性组合来表示，而前景文本和图形产生尖锐的不连续性并且不能由此顺利的表示。该算法使用最小绝对偏差法分离背景和前景以将光滑模型拟合到图像像素。该算法已经在来自用于屏幕内容编码的HEVC标准测试序列的多个图像上进行了测试，并且被示出为具有优于其他流行方法（诸如基于k-means聚类的DjVu分割和形状原始提取和编码（SPEC）算法。这种背景/前景分割是重要的用于文本提取的前处理步骤，以及用于压缩屏幕内容图像的背景和前景的单独编码。

##### URL
[https://arxiv.org/abs/1501.03755](https://arxiv.org/abs/1501.03755)

##### PDF
[https://arxiv.org/pdf/1501.03755](https://arxiv.org/pdf/1501.03755)

