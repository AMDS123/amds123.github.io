---
layout: post
title: "Cell Detection with Star-convex Polygons"
date: 2018-06-09 19:38:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Uwe Schmidt, Martin Weigert, Coleman Broaddus, Gene Myers
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic detection and segmentation of cells and nuclei in microscopy images is important for many biological applications. Recent successful learning-based approaches include per-pixel cell segmentation with subsequent pixel grouping, or localization of bounding boxes with subsequent shape refinement. In situations of crowded cells, these can be prone to segmentation errors, such as falsely merging bordering cells or suppressing valid cell instances due to the poor approximation with bounding boxes. To overcome these issues, we propose to localize cell nuclei via star-convex polygons, which are a much better shape representation as compared to bounding boxes and thus do not need shape refinement. To that end, we train a convolutional neural network that predicts for every pixel a polygon for the cell instance at that position. We demonstrate the merits of our approach on two synthetic datasets and one challenging dataset of diverse fluorescence microscopy images.

##### Abstract (translated by Google)
显微镜图像中细胞和细胞核的自动检测和分割对于许多生物学应用是重要的。最近成功的基于学习的方法包括每像素单元分割和随后的像素分组，或边界框的本地化以及随后的形状细化。在拥挤小区的情况下，这些可能容易出现分段错误，例如错误地合并边界单元或由于边界框近似较差而抑制有效的单元实例。为了克服这些问题，我们建议通过星形 - 凸多边形来定位细胞核，与边界框相比，这是一种更好的形状表示，因此不需要形状细化。为此，我们训练一个卷积神经网络，为每个像素预测该位置的细胞实例的多边形。我们展示了我们的方法在两个合成数据集和一个具有挑战性的不同荧光显微图像数据集上的优点。

##### URL
[http://arxiv.org/abs/1806.03535](http://arxiv.org/abs/1806.03535)

##### PDF
[http://arxiv.org/pdf/1806.03535](http://arxiv.org/pdf/1806.03535)

