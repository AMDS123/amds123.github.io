---
layout: post
title: "Fast Single Image Dehazing via Multilevel Wavelet Transform based Optimization"
date: 2019-04-18 02:38:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Optimization Detection
author: Jiaxi He, Frank Z. Xing, Ran Yang, Cishen Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The quality of images captured in outdoor environments can be affected by poor weather conditions such as fog, dust, and atmospheric scattering of other particles. This problem can bring extra challenges to high-level computer vision tasks like image segmentation and object detection. However, previous studies on image dehazing suffer from a huge computational workload and corruption of the original image, such as over-saturation and halos. In this paper, we present a novel image dehazing approach based on the optical model for haze images and regularized optimization. Specifically, we convert the non-convex, bilinear problem concerning the unknown haze-free image and light transmission distribution to a convex, linear optimization problem by estimating the atmosphere light constant. Our method is further accelerated by introducing a multilevel Haar wavelet transform. The optimization, instead, is applied to the low frequency sub-band decomposition of the original image. This dimension reduction significantly improves the processing speed of our method and exhibits the potential for real-time applications. Experimental results show that our approach outperforms state-of-the-art dehazing algorithms in terms of both image reconstruction quality and computational efficiency. For implementation details, source code can be publicly accessed via <a href="http://github.com/JiaxiHe/Image-and-Video-Dehazing.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08573](http://arxiv.org/abs/1904.08573)

##### PDF
[http://arxiv.org/pdf/1904.08573](http://arxiv.org/pdf/1904.08573)

