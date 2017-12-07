---
layout: post
title: "Fully Automatic Segmentation of Lumbar Vertebrae from CT Images using Cascaded 3D Fully Convolutional Networks"
date: 2017-12-05 07:24:57
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Rens Janssens, Guodong Zeng, Guoyan Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to address the challenging problem of segmentation of lumbar vertebrae from CT images acquired with varying fields of view. Our method is based on cascaded 3D Fully Convolutional Networks (FCNs) consisting of a localization FCN and a segmentation FCN. More specifically, in the first step we train a regression 3D FCN (we call it "LocalizationNet") to find the bounding box of the lumbar region. After that, a 3D U-net like FCN (we call it "SegmentationNet") is then developed, which after training, can perform a pixel-wise multi-class segmentation to map a cropped lumber region volumetric data to its volume-wise labels. Evaluated on publicly available datasets, our method achieved an average Dice coefficient of 95.77 $\pm$ 0.81% and an average symmetric surface distance of 0.37 $\pm$ 0.06 mm.

##### Abstract (translated by Google)
我们提出了一种方法来解决从不同视野获得的CT图像分割腰椎的挑战性问题。我们的方法是基于由定位FCN和分段FCN组成的级联3D全卷积网络（FCN）。更具体地说，在第一步中，我们训练回归3D FCN（我们称之为“本地化网络”）来找到腰部区域的边界框。之后，开发出像FCN（我们称之为“SegmentationNet”）的3D U网，其在训练后可以执行像素级的多级分割，以将裁剪的木材区域体积数据映射到其体积方向标签。在公开可用的数据集上评估，我们的方法实现了平均Dice系数95.77 $ \ pm $ 0.81％和平均对称表面距离0.37 $ \ pm $ 0.06毫米。

##### URL
[http://arxiv.org/abs/1712.01509](http://arxiv.org/abs/1712.01509)

##### PDF
[http://arxiv.org/pdf/1712.01509](http://arxiv.org/pdf/1712.01509)

