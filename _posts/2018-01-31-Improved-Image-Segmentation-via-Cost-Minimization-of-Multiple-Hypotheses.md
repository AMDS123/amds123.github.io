---
layout: post
title: "Improved Image Segmentation via Cost Minimization of Multiple Hypotheses"
date: 2018-01-31 22:37:46
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation
author: Marc Bosch, Christopher M. Gifford, Austin G. Dress, Clare W. Lau, Jeffrey G. Skibo, Gordon A. Christie
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is an important component of many image understanding systems. It aims to group pixels in a spatially and perceptually coherent manner. Typically, these algorithms have a collection of parameters that control the degree of over-segmentation produced. It still remains a challenge to properly select such parameters for human-like perceptual grouping. In this work, we exploit the diversity of segments produced by different choices of parameters. We scan the segmentation parameter space and generate a collection of image segmentation hypotheses (from highly over-segmented to under-segmented). These are fed into a cost minimization framework that produces the final segmentation by selecting segments that: (1) better describe the natural contours of the image, and (2) are more stable and persistent among all the segmentation hypotheses. We compare our algorithm's performance with state-of-the-art algorithms, showing that we can achieve improved results. We also show that our framework is robust to the choice of segmentation kernel that produces the initial set of hypotheses.

##### Abstract (translated by Google)
图像分割是许多图像理解系统的重要组成部分。它旨在以空间和感知上一致的方式对像素进行分组。通常，这些算法具有控制所产生的过度分割程度的参数集合。正确选择人类感知分组的参数仍然是一个挑战。在这项工作中，我们利用不同的参数选择产生的细分的多样性。我们扫描分割参数空间，并生成一个图像分割假设的集合（从高度分割到欠分割）。这些被投入到一个成本最小化框架中，该框架通过选择以下部分来产生最终的分割：（1）更好地描述图像的自然轮廓，以及（2）在所有分割假设中更稳定和持久。我们将算法的性能与最先进的算法进行比较，表明我们可以获得更好的结果。我们还展示了我们的框架对产生最初假设集合的分割内核的选择是强健的。

##### URL
[http://arxiv.org/abs/1802.00088](http://arxiv.org/abs/1802.00088)

##### PDF
[http://arxiv.org/pdf/1802.00088](http://arxiv.org/pdf/1802.00088)

