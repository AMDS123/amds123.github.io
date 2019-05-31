---
layout: post
title: "Memory-efficient and fast implementation of local adaptive binarization methods"
date: 2019-05-30 13:17:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Chungkwong Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Binarization is widely used as an image preprocessing step to separate object especially text from background before recognition. For noisy images with uneven illumination, threshold values should be computed pixel by pixel to obtain a good segmentation. Since local threshold values typically depend on moments-based statistics such as mean and variance of gray levels inside rectangular windows, integral images are commonly used to accelerate the calculation. However, integral images are memory consuming. For Sauvola's method, the two integral images occupy $16HW$ bytes given a $H\times W$ input image. By using a recursive technique to avoid integral images, memory usage of intermediate data structures can be reduced significantly to $6\min\{H,W\}$ bytes, while the time complexity remains $O(HW)$ independent of window size. Therefore, the proposed implementation enable various local adaptive binarization methods to be applied in real-time use cases on devices with limited resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13038](http://arxiv.org/abs/1905.13038)

##### PDF
[http://arxiv.org/pdf/1905.13038](http://arxiv.org/pdf/1905.13038)

